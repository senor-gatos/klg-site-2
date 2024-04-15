<script>
    import ContactForm from "../../lib/components/contact-form.svelte";
    import Navbar from "../../lib/components/Navbar.svelte";
    import  Footer  from "../../lib/components/Footer.svelte";

  </script>

<body class="font-[Poppins]">

    <Navbar />


<div>

    <div class="flex flex-row">
        <div class="text-center">
            <h1 class="pt-72 md:text-5xl">
                Contact Us.

            </h1>
            <h2 class="pt-4 sm:text-sm md:text-2xl">
                Sign up for our newsletter, or 
            </h2>
            <h2 class=" sm:text-sm md:text-2xl">
                Ask a question,
            </h2>
            <h2 class="pt-4 sm:text-sm md:text-2xl">
                We're here to help.
            </h2>
            <ContactForm />
        </div>
        <div>
            <h2 class="pt-72 md:pl-64 sm:text-lg md:text-3xl">
                Call.
            </h2>
            <h2 class="md:pl-64 sm:text-lg md:text-2xl text-blue-800">
                <a href="tel:212-537-6714">212-537-6714</a>
            </h2>
            <h2 class="pt-12 md:pl-64 sm:text-lg md:text-3xl">
                Email.
            </h2>
            <h2 class="md:pl-64 sm:text-lg md:text-2xl text-blue-800">
                <a href="mailto: info@thekatzlawgroup.com">info@thekatzlawgroup.com</a>
            </h2>
            <h2 class="pt-12 md:pl-64 sm:text-lg md:text-3xl">
                Mail.
            </h2>
            <h2 class="md:pl-64 sm:text-lg md:text-2xl text-blue-800">
                The Katz Law Group, P.C. <br>
                75 South Broadway <br>
                White Plains, NY 10601
            </h2>
        </div>
    </div>

    <section class="pt-12">
        <Footer />
    </section>

</div>


</body>