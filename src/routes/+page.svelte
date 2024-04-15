<script>
  import logo from "../lib/images/logo-no-background.svg"
  import plane from "../lib/images/plane.png"

  import earth from "../lib/images/earth.png"
  import Navbar from '../lib/components/Navbar.svelte';
  import CardBI from '../lib/components/CardBI.svelte';
  import CardE2 from '../lib/components/CardE2.svelte';
  import CardL1 from '../lib/components/CardL1.svelte';
  import Card from '../lib/components/Card.svelte';
  import  Footer  from "../lib/components/Footer.svelte";

  import { Rating, AdvancedRating, ScoreRating } from 'flowbite-svelte';

</script>

<svelte:head>
	<title>KLG Law</title>
	<meta name="description" content="KLG Site" />
</svelte:head>

<body class="font-[Sans-Serif] ">
	<Navbar />
	
<section class=" ">

        <div class=" w-full ">
			<div class="flex justify-center items-center pl-4 pt-72">
				<div class="flex flex-row">

					<img src={logo} class="me-3 h-44 md:h-64 max-w-full" alt="KLG Logo" />
				</div>

			</div>
			<div class="text-center">
				<h2 class="pt-8 text-2xl">
					Your Immigration Law Firm.
				</h2>
				<h2 class="text-2xl">
					<p>We handle a full range of US immigration law services.</p>
				</h2>
				<div class="pt-16">
					<button class="hover:text-orange-300 text-white bg-orange-500 rounded-2xl pl-5 pr-5 shadow-md" type="button"><a href="/services" class="hover:text-orange-300">Learn More</a></button>
				</div>
			</div>

        </div>

</section>

<section>

	<h1 class="pt-72 sm:text-lg md:text-3xl">
		Highlights
	</h1>

	<div class="pt-8 md:flex flex-row">
		<div class="pt-2 pl-12">
			<CardBI />
		</div>
		<div class="pt-2 pl-12">
			<CardL1 />
		</div>
		<div class="pt-2 pl-12">
			<CardE2 />
		</div>
	</div>

</section>

<section class="pt-64">

	<Rating id="example-1b" total={5} size={50} rating={5} />
	<h1 class="md:pt-12 md:pb-4 sm:text-lg md:text-5xl">
		Experience Matters
	</h1>
	<h2 class=" sm:text-sm md:text-3xl">
		Over 25 Years
		</h2>
	<div class="flex flex-row pt-12">

		<h2 class="text-2xl pr-64">
			2000 Approvals and counting
		</h2>
		<h2 class=" text-2xl">
			Clients from all over the world
		</h2>
	</div>	
	<img src={earth} alt="pic of the earth"/>
</section>


<section class="pt-12"> 
	<Footer />
</section>

</body>
<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

    a{
      color: white;
    }


</style>
