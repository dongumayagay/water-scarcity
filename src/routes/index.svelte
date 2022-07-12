<script>
	import Drop from '../lib/components/Drop.svelte';
	import Header from '../lib/components/Header.svelte';
	import Rain from '../lib/components/Rain.svelte';
	import TextWater from '../lib/components/TextWater.svelte';
</script>

<main class="h-screen w-screen snap-mandatory snap-y overflow-scroll">
	<section class="bg-red-900 h-screen w-screen snap-start relative">
		<video class="h-full w-full object-cover sm:object-left" src="gripo.mp4" muted autoplay loop
			><track kind="captions" /></video
		>

		<div class="absolute top-0 w-full h-full sm:p-32">
			<main class="lg:w-1/3 lg:ml-auto flex flex-col items-end">
				<h1 class="text-5xl font-bold text-center border-yellow-400  border-b-4 text-black">
					Global Water Crisis
				</h1>
				<p class="text-black/80 text-lg py-4 sm:text-right">
					Lorem, ipsum dolor sit amet consectetur adipisicing elit. Expedita modi possimus minus
					dicta suscipit est deleniti pariatur, ipsum repellat maiores obcaecati ad laboriosam alias
					velit quis quod! Quae animi placeat, explicabo esse quam dolore cumque qui quidem
					deserunt, quia ut ipsa fugiat minima voluptate alias, dolorem sequi? Nihil, impedit
					repellat ad totam repudiandae, libero doloribus perspiciatis sed nobis animi, mollitia
					reprehenderit. Provident ipsum nam at cum modi quasi dolore necessitatibus perspiciatis
					eum voluptate maiores nemo voluptas ipsam explicabo alias voluptatibus earum cumque,
					expedita sit. Doloremque veritatis modi nihil quibusdam. Repudiandae nostrum quis deleniti
					delectus, beatae, harum id, fugiat culpa debitis aspernatur neque corporis facilis amet
					non reprehenderit voluptates distinctio tenetur laboriosam alias? Temporibus impedit
					voluptas amet nihil maxime reiciendis iure dolorum, repellat enim hic fugiat officia fuga
					provident adipisci, tempore animi illum explicabo perspiciatis? Ad laborum, est vitae
					ullam maiores nam, corrupti distinctio voluptate cupiditate nisi qui! Natus, illo quaerat!
				</p>
			</main>
		</div>
		<a href="#second" class="absolute left-1/2 bottom-10 btn btn-ghost">Continue</a>
	</section>
	<section id="second" class="bg-cyan-500 h-screen w-screen snap-start ">
		<!--  -->
		<Drop />
	</section>
	<section id="" class="bg-neutral-500 h-screen w-screen snap-start relative">
		<!--  -->
		<TextWater />
	</section>
	<section id="" class=" h-screen w-screen snap-start ">
		<!--  -->
		<Header />
	</section>

	<section id="" class="bg-sky-700 h-screen w-screen snap-start relative">
		<!--  -->
		<Rain />
	</section>
</main>
