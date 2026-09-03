<script lang="ts">
	
</script>

<svelte:head>
	<title>Brandon's Site</title>
</svelte:head>

<header class="flex justify-between mx-8 my-4">
	<span class="font-mono text-2xl md:text-3xl">Brandon Li</span>
	<nav class="flex flex-row gap-4 md:gap-6 justify-center items-center">
		<a href="https://github.com/brandonfglx" target="_blank" title="GitHub">
			<svg class="size-6 md:size-8" viewBox="0 0 25 23" xmlns="http://www.w3.org/2000/svg">
				<path fill="currentColor" d="M 10.3599 17.3462 C 7.2016 16.9634 4.9765 14.6904 4.9765 11.7476 C 4.9765 10.5513 5.4072 9.2593 6.125 8.3979 C 5.814 7.6084 5.8618 5.9336 6.2207 5.2397 C 7.1777 5.1201 8.4697 5.6226 9.2354 6.3164 C 10.1445 6.0293 11.1015 5.8857 12.2739 5.8857 C 13.4463 5.8857 14.4033 6.0293 15.2646 6.2925 C 16.0064 5.6226 17.3223 5.1201 18.2793 5.2397 C 18.6142 5.8857 18.6621 7.5606 18.3511 8.374 C 19.1167 9.2832 19.5234 10.5034 19.5234 11.7476 C 19.5234 14.6904 17.2983 16.9155 14.0923 17.3223 C 14.9057 17.8486 15.456 18.9971 15.456 20.313 L 15.456 22.8013 C 15.456 23.5191 16.0542 23.9258 16.772 23.6387 C 21.1026 21.9878 24.5 17.6572 24.5 12.2979 C 24.5 5.5268 18.9971 0 12.2261 0 C 5.4551 0 -0 5.5268 -0 12.2979 C -0 17.6094 3.3735 22.0117 7.9194 23.6626 C 8.5654 23.9018 9.1875 23.4712 9.1875 22.8252 L 9.1875 20.9111 C 8.8526 21.0547 8.4219 21.1504 8.039 21.1504 C 6.46 21.1504 5.5268 20.2891 4.8569 18.686 C 4.5938 18.0401 4.3067 17.6572 3.7563 17.5855 C 3.4693 17.5615 3.3735 17.4419 3.3735 17.2983 C 3.3735 17.0112 3.8521 16.7959 4.3306 16.7959 C 5.0244 16.7959 5.6226 17.2266 6.2446 18.1118 C 6.7232 18.8057 7.2256 19.1167 7.8237 19.1167 C 8.4219 19.1167 8.8047 18.9014 9.355 18.3511 C 9.7617 17.9443 10.0727 17.5855 10.3599 17.3462 Z"></path>
			</svg>
		</a>
		<a href="https://youtube.com/@brandonfglx" target="_blank" title="YouTube">
			<svg class="size-6 md:size-8" viewBox="0 0 20 14" xmlns="http://www.w3.org/2000/svg">
				<path fill="currentColor" d="M7.9884 9.5859 7.9884 3.9743C9.9806 4.9117 11.5236 5.8172 13.3485 6.7935 11.8434 7.6282 9.9806 8.5647 7.9884 9.5859M19.091 1.1829C18.7473.7301 18.1616.3781 17.5381.2614 15.7052-.0866 4.271-.0876 2.4391.2614 1.9391.3552 1.4938.5815 1.1113.9336-.5004 2.4295.0047 10.4515.3931 11.751.5565 12.3134.7677 12.7193 1.0336 12.9856 1.3763 13.3376 1.8455 13.58 2.3844 13.6887 3.8935 14.0008 11.668 14.1753 17.5062 13.7355 18.0441 13.6418 18.5202 13.3915 18.8958 13.0245 20.3859 11.5346 20.2843 3.0617 19.091 1.1829"></path>
			</svg>
		</a>
		<a href="https://www.linkedin.com/in/brandon-li-369679432/" target="_blank" title="LinkedIn">
			<svg class="size-6 md:size-8" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
				<path fill="currentColor" d="M14.72-0H1.37C1.1979-.0081 1.0259.0179.8639.0763.7019.1348.553.2247.4257.3408.2985.4569.1954.597.1223.753.0493.909.0077 1.0779 0 1.25V14.63C.0101 14.9901.1577 15.3328.4124 15.5875.6672 15.8423 1.0098 15.9899 1.37 16H14.72C15.0701 15.9844 15.4002 15.8322 15.6395 15.5761 15.8788 15.32 16.0082 14.9804 16 14.63V1.25C16.0029 1.0825 15.9715.9162 15.9078.7612 15.8441.6063 15.7494.466 15.6295.349 15.5097.2319 15.3672.1406 15.2108.0806 15.0544.0206 14.8874-.0069 14.72-0ZM5 13.34H2.67V6.21H5V13.34ZM3.89 5.13C3.7274 5.1356 3.5654 5.1076 3.4142 5.0477 3.2629 4.9877 3.1257 4.8972 3.0111 4.7817 2.8966 4.6662 2.8071 4.5282 2.7484 4.3765 2.6897 4.2247 2.663 4.0625 2.67 3.9 2.6628 3.7357 2.69 3.5717 2.75 3.4185 2.8099 3.2654 2.9011 3.1264 3.0179 3.0106 3.1346 2.8948 3.2743 2.8047 3.4279 2.746 3.5816 2.6874 3.7458 2.6615 3.91 2.67 4.0726 2.6643 4.2346 2.6923 4.3858 2.7523 4.5371 2.8122 4.6743 2.9028 4.7889 3.0183 4.9034 3.1338 4.9929 3.2717 5.0516 3.4235 5.1103 3.5752 5.137 3.7374 5.13 3.9 5.1372 4.0643 5.11 4.2282 5.0501 4.3814 4.9901 4.5346 4.8989 4.6735 4.7821 4.7893 4.6654 4.9051 4.5257 4.9953 4.3721 5.0539 4.2184 5.1126 4.0542 5.1385 3.89 5.13ZM13.34 13.34H11V9.44C11 8.51 10.67 7.87 9.84 7.87 9.5822 7.8722 9.3313 7.9541 9.1219 8.1045 8.9124 8.2549 8.7546 8.4664 8.67 8.71 8.605 8.8926 8.5778 9.0865 8.59 9.28V13.34H6.29V6.21H8.59V7.21C8.7945 6.8343 9.0988 6.5225 9.4694 6.3089 9.84 6.0954 10.2624 5.9885 10.69 6 12.2 6 13.34 7 13.34 9.13V13.34Z"></path>
			</svg>
		</a>
	</nav>
</header>
<main class="mx-16 my-4 flex flex-col gap-2 gap-y-4 md:grid md:grid-cols-12">
	<section class="rounded-3xl bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-3 lg:p-4 flex flex-col items-center gap-2 md:col-span-4 lg:col-span-3">
		<h1 class="font-mono text-center p-1 text-2xl lg:p-2">
			Hello!
		</h1>
		<img src="https://avatars.githubusercontent.com/u/173737496?v=4" alt="Brandon Li" class="font-mono text-center rounded-full aspect-square object-cover w-40">
	</section>
	<section class="rounded-3xl bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-3 lg:p-4 flex flex-col gap-2 md:col-span-8 lg:col-span-6">
		<h1 class="font-mono text-center p-1 text-2xl lg:p-2">
			About Me
		</h1>
		<p class="font-mono text-sm md:text-base">
			Hello, I'm Brandon Li, a junior at Monta Vista High School in Cupertino, CA. I am a successful student and an aspiring programmer with experience in Java and Rust. I am currently tinkering with animation using Blender and game design using Godot. Feel free to reach out if you are interested in partnering or just having a chat!
		</p>
	</section>
	<section class="rounded-3xl bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-3 lg:p-4 flex flex-col gap-2 md:col-span-4 lg:col-span-3">
		<h1 class="font-mono text-center p-1 text-2xl lg:p-2">
			Academics
		</h1>
		<ul class="font-mono list-disc list-inside text-sm md:text-base">
			<li>
				AP Computer Science A (5/5)
			</li>
			<li>
				MVRT Software Engineer
			</li>
			<li>
				MVRT Cadology Teacher
			</li>
			<li>
				Steel City Codes Tutor
			</li>
			<li>
				Introduction to Java Student Tutor / Mentor
			</li>
		</ul>
	</section>
	<section class="rounded-3xl bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-3 lg:p-4 flex flex-col gap-2 md:col-span-4 lg:col-span-5 lg:col-start-2">
		<h1 class="font-mono text-center p-1 text-2xl lg:p-2">
			I Am Interested In
		</h1>
		<ul class="font-mono list-disc list-inside text-sm md:text-base">
			<li>Web Development (Svelte, HTML, CSS, JS/TS)</li>
			<li>Systems Programming (Java)</li>
			<li>Low-Level Programming (Rust)</li>
			<li>Game Development (Godot)</li>
			<li>Modeling & Animation (Blender)</li>
		</ul>
	</section>
	<section class="rounded-3xl bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-3 lg:p-4 flex flex-col gap-2 md:col-span-4 lg:col-span-5">
		<h1 class="font-mono text-center p-1 text-2xl lg:p-2">
			I Am Participating In
		</h1>
		<ul class="font-mono list-disc list-inside text-sm md:text-base">
			<li>
				Hack Club - this website is one of my submissions!
			</li>
			<li>
				MVRT - participated in 2026 Rebuilt competition
			</li>
			<li>
				Steel City Codes - Tutor for Fall 2025 & Spring 2026
			</li>
			<li>
				Tutoring - Java, Physics, & Math
			</li>
		</ul>
	</section>
	<section class="rounded-3xl bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-3 lg:p-4 flex flex-col gap-2 md:col-span-12">
		<h1 class="font-mono text-center p-1 text-2xl lg:p-2">
			Project Showcase
		</h1>
		<div class="flex flex-col gap-4 md:flex-row md:justify-stretch">
			<section class="rounded-2xl bg-gray-50 dark:bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-4">
				<!-- <img src="" alt="Personal Website" class="text-center"> -->
				<h1 class="font-mono text-center pt-1 text-lg lg:text-xl">
					Personal Website
				</h1>
				<h2 class="font-mono text-center pb-1 text-sm lg:text-lg text-green-500">
					A website with a personal touch.
				</h2>
				<p>
					A personal website that explains everything about me. Made with Svelte, TailwindCSS, and some light HTML, the website is sleek and concise with its information.
				</p>
			</section>
			<section class="rounded-2xl bg-gray-50 dark:bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-4">
				<!-- <img src="" alt="TermTab" class="text-center"> -->
				<h1 class="font-mono text-center pt-1 text-lg lg:text-xl">
					TermTab
				</h1>
				<h2 class="font-mono text-center pb-1 text-sm lg:text-lg text-green-500">
					GUIs are boring; try a terminal window instead!
				</h2>
				<p>
					A fully-featured start page stylized like a terminal. Search instantly by typing your query into the command line or view more details by calling programs or clicking on widgets. And its fully customizable to the user's liking.
				</p>
			</section>
			<section class="rounded-2xl bg-gray-50 dark:bg-fglx-glass border-fglx-border-glass backdrop-blur-md border p-4">
				<!-- <img src="" alt="TermOS" class="text-center"> -->
				<h1 class="font-mono text-center p-1 text-lg lg:text-xl">
					TermOS
				</h1>
				<h2 class="font-mono text-center pb-1 text-sm lg:text-lg text-green-500">
					What if the terminal is the OS and much more than a terminal?
				</h2>
				<p>
					An operating system stylized like a terminal that runs on your browser. Write files, make custom configurations, browse, and listen to music all through a single webpage!
				</p>
			</section>
		</div>
	</section>
</main>
<footer class="my-2">
	<p class="text-center font-mono text-sm">&copy;2026 Brandon Li</p>
</footer>