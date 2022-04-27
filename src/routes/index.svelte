<script context="module">
	import { browser, dev } from '$app/env';

	// // we don't need any JS on this page, though we'll load
	// // it in dev so that we get hot module replacement...
	// export const hydrate = dev;

	// // ...but if the client-side router is already loaded
	// // (i.e. we came here from elsewhere in the app), use it
	export const router = browser;

	// // since there's no dynamic data here, we can prerender
	// // it so that it gets served as a static asset in prod
	export const prerender = true;
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<main>
    <!-- Require css -->
	<section class="relative">
    <div class="max-w-8xl mx-auto px-4 sm:px-6 flex flex-col items-center bg-cover" style="background-image: url(/img/Eruwa.png)">
	  <!-- {/* Hero content */} -->
		<!-- {/* Section header */} -->
	
	  <img class="object-center h-80 mt-10" src="/img/Innoviume.svg" alt="Innoviume" />	
	  <!-- </div>	 -->
		<div class="text-center pb-12 md:pb-16">
		  <h1 class="text-5xl md:text-6xl font-extrabold leading-tighter tracking-tighter text-black m-10" data-aos="zoom-y-out">innoviume </h1>
		  <!-- <span class="text-3xl md:text-3xl font-extrabold leading-tighter tracking-tighter mb-4 bg-clip-text text-transparent bg-gradient-to-r from-white to-yellow-300">The tech mineral company</span> -->
		  <div class="max-w-3xl mx-auto">
			<p class="text-xl text-white mb-8" data-aos="zoom-y-out" data-aos-delay="150">Mining start-up focused on the search and discovery of critical minerals that power advances in world technology.</p>
			<div class="max-w-xs mx-auto sm:max-w-none sm:flex sm:justify-center" data-aos="zoom-y-out" data-aos-delay="300">
			  <!-- <div>
				<a class="btn text-white bg-blue-600 hover:bg-blue-700 w-full mb-4 sm:w-auto sm:mb-0" href="#0">Start free trial</a>
			  </div> -->
			  <div>
				<!-- <a class="btn text-white bg-yellow-900 hover:bg-gray-500 w-full sm:w-auto sm:ml-0" href="/about">Learn more</a> -->
			  </div>
			</div>
		  </div>
		</div>
	</div>
  </section>
  <section class="relative bg-gray-500" >
	<div class="max-w-6xl mx-auto px-4 sm:px-6">
	  <!-- {/* Hero content */} -->
	  <div class="pt-32 pb-12 md:pt-40 md:pb-20">
		<!-- {/* Section header */} -->
		<div class="text-center pb-12 md:pb-16">
		  <!-- <h1 class="text-5xl md:text-6xl font-extrabold  leading-tighter tracking-tighter mb-4" data-aos="zoom-y-out">Petraton </h1> -->
		  <span class="text-3xl md:text-3xl font-extrabold leading-tighter tracking-tighter mb-4 bg-clip-text text-transparent bg-gradient-to-r from-gray-100 to-yellow-100">Value Driven</span>
		  <div class="max-w-3xl mx-auto">
			<p class="text-xl text-gray-100 mb-8" data-aos="zoom-y-out" data-aos-delay="150">We identify strategic mineral greenfields, explore the area, delineate the anomalous bodies, quantify the resources associated with these deposits and extract them efficiently.
			</p>
			<div class="max-w-xs mx-auto sm:max-w-none sm:flex sm:justify-center" data-aos="zoom-y-out" data-aos-delay="300">
			  <!-- <div>
				<a class="btn text-white bg-blue-600 hover:bg-blue-700 w-full mb-4 sm:w-auto sm:mb-0" href="#0">Start free trial</a>
			  </div> -->
			  <div>
				<!-- <a class="btn text-white bg-gray-700 hover:bg-yellow-500 w-full sm:w-auto sm:ml-0" href="/projects">Here's how!</a> -->
			  </div>
			</div>
		  </div>
		</div>
	</div>
  </section>


      <section class="relative">

      <!-- {/* Section background (needs .relative class on parent and next sibling elements) */} -->
      <div class="absolute inset-0 top-1/2 md:mt-24 lg:mt-0 bg-yellow-400 pointer-events-none" aria-hidden="true"></div>

      <div class="relative max-w-6xl mx-auto px-4 sm:px-6">
        <div class="py-12 md:py-20">

          <!-- {/* Section header */} -->
          <div class="max-w-3xl mx-auto text-center pb-12 md:pb-20">
			<span class="text-3xl md:text-3xl font-extrabold leading-tighter tracking-tighter mb-4 bg-clip-text text-transparent bg-gradient-to-r from-gray-500 to-yellow-900">Strong Position in the Value Chain</span>
            <p class="text-xl text-yellow-800">Positioned to generate significant impact across the mineral industry chain.</p>
          </div>

          <!-- {/* Items */} -->
          <div class="max-w-sm mx-auto grid gap-6 md:grid-cols-2 lg:grid-cols-3 items-start md:max-w-2xl lg:max-w-none">

            <!-- {/* 1st item */} -->
            <div class="relative flex flex-col items-center p-6 bg-white rounded shadow-xl">
              <svg class="w-16 h-16 p-1 -mt-1 mb-2" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                <g fill="none" fillRule="evenodd">
                  <rect class="fill-current text-yellow-800" width="64" height="64" rx="32" />
                  <g strokeWidth="2">
                    <path class="stroke-current text-yellow-300" d="M34.514 35.429l2.057 2.285h8M20.571 26.286h5.715l2.057 2.285" />
                    <path class="stroke-current text-white" d="M20.571 37.714h5.715L36.57 26.286h8" />
                    <path class="stroke-current text-yellow-300" strokeLinecap="square" d="M41.143 34.286l3.428 3.428-3.428 3.429" />
                    <path class="stroke-current text-white" strokeLinecap="square" d="M41.143 29.714l3.428-3.428-3.428-3.429" />
                  </g>
                </g>
              </svg>
              <h4 class="text-xl font-bold leading-snug tracking-tight mb-1">Exploration Program</h4>
              <p class="text-yellow-800 text-center">We utilize modern exploration techniques in the search for new mineral resources.</p>
            </div>

            <!-- {/* 2nd item */} -->
            <div class="relative flex flex-col items-center p-6 bg-white rounded shadow-xl">
              <svg class="w-16 h-16 p-1 -mt-1 mb-2" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                <g fill="none" fillRule="evenodd">
                  <rect class="fill-current text-yellow-800" width="64" height="64" rx="32" />
                  <g strokeWidth="2" transform="translate(19.429 20.571)">
                    <circle class="stroke-current text-white" strokeLinecap="square" cx="12.571" cy="12.571" r="1.143" />
                    <path class="stroke-current text-white" d="M19.153 23.267c3.59-2.213 5.99-6.169 5.99-10.696C25.143 5.63 19.514 0 12.57 0 5.63 0 0 5.629 0 12.571c0 4.527 2.4 8.483 5.99 10.696" />
                    <path class="stroke-current text-yellow-300" d="M16.161 18.406a6.848 6.848 0 003.268-5.835 6.857 6.857 0 00-6.858-6.857 6.857 6.857 0 00-6.857 6.857 6.848 6.848 0 003.268 5.835" />
                  </g>
                </g>
              </svg>
              <h4 class="text-xl font-bold leading-snug tracking-tight mb-1">Artificial Intelligence</h4>
              <p class="text-yellow-800 text-center">Uses Machine Learning Algorithms in the search for critical minerals.</p>
            </div>

            <!-- {/* 3rd item */} -->
            <div class="relative flex flex-col items-center p-6 bg-white rounded shadow-xl">
              <svg class="w-16 h-16 p-1 -mt-1 mb-2" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                <g fill="none" fillRule="evenodd">
                  <rect class="fill-current text-yellow-800" width="64" height="64" rx="32" />
                  <g strokeLinecap="square" strokeWidth="2">
                    <path class="stroke-current text-blue-300" d="M38.826 22.504a9.128 9.128 0 00-13.291-.398M35.403 25.546a4.543 4.543 0 00-6.635-.207" />
                    <path class="stroke-current text-white" d="M19.429 25.143A6.857 6.857 0 0126.286 32v1.189L28 37.143l-1.714.571V40A2.286 2.286 0 0124 42.286h-2.286v2.285M44.571 25.143A6.857 6.857 0 0037.714 32v1.189L36 37.143l1.714.571V40A2.286 2.286 0 0040 42.286h2.286v2.285" />
                  </g>
                </g>
              </svg>
              <h4 class="text-xl font-bold leading-snug tracking-tight mb-1">Blockchain</h4>
              <p class="text-yellow-800 text-center">Using blockchain to assure only conflict-free minerals within its supply chain.</p>
            </div>

            <!-- {/* 4th item */} -->
            <div class="relative flex flex-col items-center p-6 bg-white rounded shadow-xl">
              <svg class="w-16 h-16 p-1 -mt-1 mb-2" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                <g fill="none" fillRule="evenodd">
                  <rect class="fill-current text-yellow-800" width="64" height="64" rx="32" />
                  <g transform="translate(22.857 19.429)" strokeWidth="2">
                    <path class="stroke-current text-white" strokeLinecap="square" d="M12.571 4.571V0H0v25.143h12.571V20.57" />
                    <path class="stroke-current text-white" d="M16 12.571h8" />
                    <path class="stroke-current text-white" strokeLinecap="square" d="M19.429 8L24 12.571l-4.571 4.572" />
                    <circle class="stroke-current text-yellow-300" strokeLinecap="square" cx="12.571" cy="12.571" r="3.429" />
                  </g>
                </g>
              </svg>              
              <h4 class="text-xl font-bold leading-snug tracking-tight mb-1">Geoscience Evaluation</h4>
              <p class="text-yellow-800 text-center">Expert team to determine presence, quality and quantity of mineral anomalies.</p>
            </div>

            <!-- {/* 5th item */} -->
            <div class="relative flex flex-col items-center p-6 bg-white rounded shadow-xl">
              <svg class="w-16 h-16 p-1 -mt-1 mb-2" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                <g fill="none" fillRule="evenodd">
                  <rect class="fill-current text-yellow-800" width="64" height="64" rx="32" />
                  <g strokeLinecap="square" strokeWidth="2">
                    <path class="stroke-current text-white" d="M20.571 20.571h13.714v17.143H20.571z" />
                    <path class="stroke-current text-yellow-300" d="M38.858 26.993l6.397 1.73-4.473 16.549-13.24-3.58" />
                  </g>
                </g>
              </svg>
              <h4 class="text-xl font-bold leading-snug tracking-tight mb-1">Engineering Design</h4>
              <p class="text-yellow-800 text-center">Metallurgy, Recovery and Mine Plan using industry best practices.</p>
            </div>

            <!-- {/* 6th item */} -->
            <div class="relative flex flex-col items-center p-6 bg-white rounded shadow-xl">
              <svg class="w-16 h-16 p-1 -mt-1 mb-2" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                <g fill="none" fillRule="evenodd">
                  <rect class="fill-current text-yellow-800" width="64" height="64" rx="32" />
                  <g strokeWidth="2">
                    <path class="stroke-current text-white" d="M32 37.714A5.714 5.714 0 0037.714 32a5.714 5.714 0 005.715 5.714" />
                    <path class="stroke-current text-white" d="M32 37.714a5.714 5.714 0 015.714 5.715 5.714 5.714 0 015.715-5.715M20.571 26.286a5.714 5.714 0 005.715-5.715A5.714 5.714 0 0032 26.286" />
                    <path class="stroke-current text-white" d="M20.571 26.286A5.714 5.714 0 0126.286 32 5.714 5.714 0 0132 26.286" />
                    <path class="stroke-current text-yellow-300" d="M21.714 40h4.572M24 37.714v4.572M37.714 24h4.572M40 21.714v4.572" strokeLinecap="square" />
                  </g>
                </g>
              </svg>
              <h4 class="text-xl font-bold leading-snug tracking-tight mb-1">Develop & Mine</h4>
              <p class="text-yellow-800 text-center">Development and extraction in an environmentally friendly manner.</p>
            </div>

          </div>
<!-- 
        </div> -->
      </div>
    </section>
  </main>


  