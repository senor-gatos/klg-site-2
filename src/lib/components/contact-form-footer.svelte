<script>
  
    let status = "";
    const handleSubmit = async data => {
        status = 'Submitting...'
        const formData = new FormData(data.currentTarget)
        const object = Object.fromEntries(formData);
        const json = JSON.stringify(object);

        const response = await fetch("https://api.web3forms.com/submit", {
            method: "POST",
            headers: {
                "Content-Type": "application/json",
                Accept: "application/json",
            },
            body: json
        });
        const result = await response.json();
        if (result.success) {
            console.log(result);
            status = result.message || "Success"
        }
    }
  </script>

<form on:submit|preventDefault={handleSubmit}>
    <div class="pt-32 flex flex-col">
        <div>
            <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
            <label class="pl-64 pr-4 ">Name:</label>
            <input class="rounded-lg" type="text" name="name" required />
         </div>
        <div class="pt-2">
            <label class="pl-64 pr-4">Email:</label>
            <input class="rounded-lg" type="email" name="email" required />
        </div>
        <div class="pt-4">
            <label class="pl-64 pr-5">Message:</label>
        </div>
        <div class="pl-64 pr-5">
            <textarea class="rounded-lg pl-2 pr-2" name="message" required rows="3"></textarea>
        </div>
        <div class="pl-64 pr-5">
            <input class="hover:text-orange-300 text-white bg-orange-500 rounded-2xl pl-5 pr-5 shadow-md" type="submit" />
        </div>
    </div>
</form>

<div>{status}</div>