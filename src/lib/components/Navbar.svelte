<script>
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, ImagePlaceholder, Skeleton, TextPlaceholder } from 'flowbite-svelte';
    import logo from '../images/logo-no-background.svg';
  </script>
  
  <div class=" relative px-12 font-[Poppins]">
    <Navbar class=" bg-blue-900 px-2 sm:px-8 py-2.5 fixed w-full z-20 top-0 start-0 border-b">
      <NavBrand href="/">
        <img src={logo} class="me-3 h-8 sm:h-32" alt="KLG Logo" />
        <span class="text-white text-lg">The Katz Law Group</span>
      </NavBrand>
      <NavHamburger class=""/>

      <NavUl class="dark:bg-gray-900">
        <NavLi href="/"><span class="md:text-white md:text-lg hover:text-orange-300 font-[Lato]">Home</span></NavLi>
        <NavLi href="/about"><span class="md:text-white md:text-lg hover:text-orange-300 font-[Lato]">About</span></NavLi>
        <NavLi href="/services"><span class="md:text-white md:text-lg hover:text-orange-300">Services</span></NavLi>
        <NavLi href="/resources"><span class="md:text-white md:text-lg hover:text-orange-300">Resources</span></NavLi>
        <!-- <NavLi href="/contact">Contact</NavLi> -->
        <button class="hover:text-orange-300 text-white md:text-lg bg-orange-500 rounded-2xl pl-5 pr-5 shadow-md"  type="button"><a href="/contact" class="hover:text-orange-300">Contact Us</a></button>

      </NavUl>
    </Navbar>
  </div>

  <style>
    a{
      color: white;
    }
  </style>


