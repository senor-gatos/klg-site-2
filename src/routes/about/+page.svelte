<script>
	import Navbar from "../../lib/components/Navbar.svelte";
	import Ira from "../../lib/components/Ira.svelte";
  	import Zila from "../../lib/components/Zila.svelte";
	import  Footer  from "../../lib/components/Footer.svelte";

</script>


<Navbar />

<section>
	<div class="font-[Sans-Sarif]">
		<div class="text-column">
			<h1 class="pt-72 pb-4 md:text-3xl">About Us</h1>

			<p class="text-xl">
				The Katz Law Group provides legal services to a variety of U.S. and Global corporate and individual clients, representing clients in the area of U.S. Immigration law.
			
				<br><br>
			</p>
				
			<p class="text-xl">
				We pride ourselves on giving first rate service, combining a broad range of local and international experience, at competitive prices, and with an emphasis on personal attention from senior attorneys. Our office has staff that speaks Spanish and Hebrew and are admitted to practice in New York, and Israel as well as various federal courts.
				<br><br>
			</p>
			<p class="text-xl">
				The attorneys at The Katz Law Group make every effort to provide each client with personal service during every step of their case. Our approach focuses on each client's background, needs, and goals, and we are committed to responding promptly to telephone calls; reporting on cases regularly, and informing clients of significant changes in the law in real time. We use cutting edge technology and efficient methods to provide service in a timely, client-oriented manner and in an ethical, friendly, and professional environment.
				<br><br>
				Whether your issue involves an employment based matter, a family based matter, removal, a waiver or other immigration issue; work on every case in our office is always performed by experienced attorneys and not paralegals or legal assistants. 
			</p>
		<p class="text-xl pt-2">
			<a href="/services"> Check out our full range of services
			</a>
			</p>
		</div>
	</div>

</section>

<section>
	<div class="pt-24">
		<div class="justify-center flex flex-row">
			<div class="pl-12">
				<Zila />
			</div>
			<div class="pl-12">
				<Ira />
			</div>
		</div>
	</div>
</section>

<section class="pt-12">
    <Footer />
</section>