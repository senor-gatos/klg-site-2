<script>
  import ContactForm from "./contact-form.svelte";
  import logo from '../images/logo-no-background.svg';
</script>

<footer class="w-full pt-12 py-20 bg-blue-900 ">
    <div class="flex flex-row">
        <div class="max-w-screen-xl mx-auto flex justify-between space-x-14">
            <div class="pl-12">
                <img src={logo} width={99} height={13} alt="The KLG Logo" />
            </div>
            <div class="text-gray-500">
                <h6 class="font-semibold font-heading"><a href="/contact">Contact</a></h6>
                <div class=" text-gray-400 flex items-start space-x-2">
                    <p>The Katz Law Group, P.C.<br>
                        75 South Broadway <br>
                        White Plains, NY 10601</p>
                </div>
                <div class="pt-2 text-gray-400">
                    <p>(212) 537-6714</p>
                </div>
                <div class="pt-2 text-gray-400">
                    <p>info@thekatzlawgroup.com</p>
                </div>
            </div>
            
            <div class="flex flex-col space-y-6 w-1/2">
                <div class="flex flex-col">
                <h6 class=" font-heading font-semibold"><a href="/about"> About</a></h6>
                <div>
                    <div class="flex flex-col">
                        <h6 class=" font-heading font-semibold"><a href="/credits"> Credits</a></h6>
                        <div>
                            <h6 class=" font-heading font-semibold"><a href="/disclaimer"> Disclaimer</a></h6>

                         </div>
            </div>
                <!-- <form class="flex flex-col space-y-6">
                    <input type="text" placeholder="Your name" />
                    <input type="email" placeholder="Your email" />
                    <textarea placeholder="Your message" rows={5} />
                    <div>
                        <button class="primary font-heading font-semibold px-8">Send</button>
                    </div>
                </form> -->            

        </div>

    </div>

</footer>
<div class="text-gray-500 flex justify-center border-neutral-300 text-center py-4 bg-blue-900 w-full">
    <p>©2024 The Katz Law Group P.C., All rights reserved</p>
</div>