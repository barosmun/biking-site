<script lang="ts">
	import '../app.postcss';
	import { AppBar } from '@skeletonlabs/skeleton';
	import IconBike from '~icons/mdi/bike';
	// import IconBicycle from '~icons/mdi/bicycle';
	// import IconBicycleCargo from '~icons/mdi/bicycle-cargo';
	// import IconBicycleBasket from '~icons/mdi/bicycle-basket';
</script>

<div class="w-full bg-surface-100-800-token py-4">
	<div class="px-8 flex justify-center items-center">
		<div class="w-0 grow flex justify-end">
			<IconBike width={80} height={80}></IconBike>
		</div>

			<h2 class="max-sm:hidden ml-8 h2 grow"> Cycling Advocates of Cuyahoga Falls</h2>		
			<h2 class="max-sm:block hidden ml-4 h4 grow"> Cycling Advocates of <br /> Cuyahoga Falls</h2>		
	</div>

	<!-- <div class="flex justify-center items-center px-8 max-md:gap-x-12 gap-x-20">
			<IconBicycleBasket width={60} height={60}></IconBicycleBasket>
			<IconBicycle width={60} height={60}></IconBicycle>
			<IconBicycleCargo width={60} height={60}></IconBicycleCargo>
	</div> -->

</div>

<div class="container mx-auto py-8 px-4">
	<slot />
</div>


