<div class="px-4 py-5 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
	<div class="relative flex items-center justify-between">
		<a href="/" aria-label="Company" title="Company" class="inline-flex items-center">
			<svg
				class="w-8 text-deep-purple-accent-400"
				viewBox="0 0 24 24"
				stroke-linejoin="round"
				stroke-width="2"
				stroke-linecap="round"
				stroke-miterlimit="10"
				stroke="currentColor"
				fill="none"
			>
				<rect x="3" y="1" width="7" height="12" />
				<rect x="3" y="17" width="7" height="6" />
				<rect x="14" y="1" width="7" height="6" />
				<rect x="14" y="11" width="7" height="12" />
			</svg>
			<span class="ml-2 text-xl font-bold tracking-wide text-gray-800 uppercase">Company</span>
		</a>
		<ul class="flex items-center hidden space-x-8 lg:flex">
			<li>
				<a
					href="/"
					aria-label="Our product"
					title="Our product"
					class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400"
					>Product</a
				>
			</li>
			<li>
				<a
					href="/"
					aria-label="Our product"
					title="Our product"
					class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400"
					>Features</a
				>
			</li>
			<li>
				<a
					href="/"
					aria-label="Product pricing"
					title="Product pricing"
					class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400"
					>Pricing</a
				>
			</li>
			<li>
				<a
					href="/"
					aria-label="About us"
					title="About us"
					class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400"
					>About us</a
				>
			</li>
		</ul>
		<ul class="flex items-center hidden space-x-8 lg:flex">
			<li>
				<a
					href="/auth"
					class="inline-flex items-center justify-center h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
					aria-label="Sign up"
					title="Sign up"
				>
					Sign up
				</a>
			</li>
		</ul>
		<!-- Mobile menu -->
		<div class="lg:hidden">
			<button
				aria-label="Open Menu"
				title="Open Menu"
				class="p-2 -mr-1 transition duration-200 rounded focus:outline-none focus:shadow-outline hover:bg-deep-purple-50 focus:bg-deep-purple-50"
			>
				<svg class="w-5 text-gray-600" viewBox="0 0 24 24">
					<path
						fill="currentColor"
						d="M23,13H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,13,23,13z"
					/>
					<path
						fill="currentColor"
						d="M23,6H1C0.4,6,0,5.6,0,5s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,6,23,6z"
					/>
					<path
						fill="currentColor"
						d="M23,20H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,20,23,20z"
					/>
				</svg>
			</button>
			<!-- Mobile menu dropdown 
        <div class="absolute top-0 left-0 w-full">
          <div class="p-5 bg-white border rounded shadow-sm">
            <div class="flex items-center justify-between mb-4">
              <div>
                <a href="/" aria-label="Company" title="Company" class="inline-flex items-center">
                  <svg class="w-8 text-deep-purple-accent-400" viewBox="0 0 24 24" stroke-linejoin="round" stroke-width="2" stroke-linecap="round" stroke-miterlimit="10" stroke="currentColor" fill="none">
                    <rect x="3" y="1" width="7" height="12"></rect>
                    <rect x="3" y="17" width="7" height="6"></rect>
                    <rect x="14" y="1" width="7" height="6"></rect>
                    <rect x="14" y="11" width="7" height="12"></rect>
                  </svg>
                  <span class="ml-2 text-xl font-bold tracking-wide text-gray-800 uppercase">Company</span>
                </a>
              </div>
              <div>
                <button aria-label="Close Menu" title="Close Menu" class="p-2 -mt-2 -mr-2 transition duration-200 rounded hover:bg-gray-200 focus:bg-gray-200 focus:outline-none focus:shadow-outline">
                  <svg class="w-5 text-gray-600" viewBox="0 0 24 24">
                    <path
                      fill="currentColor"
                      d="M19.7,4.3c-0.4-0.4-1-0.4-1.4,0L12,10.6L5.7,4.3c-0.4-0.4-1-0.4-1.4,0s-0.4,1,0,1.4l6.3,6.3l-6.3,6.3 c-0.4,0.4-0.4,1,0,1.4C4.5,19.9,4.7,20,5,20s0.5-0.1,0.7-0.3l6.3-6.3l6.3,6.3c0.2,0.2,0.5,0.3,0.7,0.3s0.5-0.1,0.7-0.3 c0.4-0.4,0.4-1,0-1.4L13.4,12l6.3-6.3C20.1,5.3,20.1,4.7,19.7,4.3z"
                    ></path>
                  </svg>
                </button>
              </div>
            </div>
            <nav>
              <ul class="space-y-4">
                <li><a href="/" aria-label="Our product" title="Our product" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Product</a></li>
                <li><a href="/" aria-label="Our product" title="Our product" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Features</a></li>
                <li><a href="/" aria-label="Product pricing" title="Product pricing" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Pricing</a></li>
                <li><a href="/" aria-label="About us" title="About us" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">About us</a></li>
                <li>
                  <a
                    href="/"
                    class="inline-flex items-center justify-center w-full h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
                    aria-label="Sign up"
                    title="Sign up"
                  >
                    Sign up
                  </a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        -->
		</div>
	</div>
</div>

<div class="relative flex flex-col-reverse py-16 lg:pt-0 lg:flex-col lg:pb-0">
	<div
		class="inset-y-0 top-0 right-0 z-0 w-full max-w-xl px-4 mx-auto md:px-0 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-7/12 lg:max-w-full lg:absolute xl:px-0"
	>
		<svg
			class="absolute left-0 hidden h-full text-white transform -translate-x-1/2 lg:block"
			viewBox="0 0 100 100"
			fill="currentColor"
			preserveAspectRatio="none slice"
		>
			<path d="M50 0H100L50 100H0L50 0Z" />
		</svg>
		<img
			class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none md:h-96 lg:h-full"
			src="https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
			alt=""
		/>
	</div>
	<div
		class="relative flex flex-col items-start w-full max-w-xl px-4 mx-auto md:px-0 lg:px-8 lg:max-w-screen-xl"
	>
		<div class="mb-16 lg:my-40 lg:max-w-lg lg:pr-5">
			<p
				class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400"
			>
				Brand new
			</p>
			<h2
				class="mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none"
			>
				Everything you<br class="hidden md:block" />
				can imagine
				<span class="inline-block text-deep-purple-accent-400">is real</span>
			</h2>
			<p class="pr-5 mb-5 text-base text-gray-700 md:text-lg">
				Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
				laudantium, totam rem aperiam, eaque ipsa quae. explicabo.
			</p>
			<div class="flex items-center">
				<a
					href="/"
					class="inline-flex items-center justify-center h-12 px-6 mr-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
				>
					Get started
				</a>
				<a
					href="/"
					aria-label=""
					class="inline-flex items-center font-semibold text-gray-800 transition-colors duration-200 hover:text-deep-purple-accent-700"
					>Learn more</a
				>
			</div>
		</div>
	</div>
</div>

<div
	class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div class="flex flex-col mb-6 lg:flex-row md:mb-10">
		<div class="lg:w-1/2">
			<h2
				class="max-w-md mb-6 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none xl:max-w-lg"
			>
				To conquer the space you must trust.
			</h2>
		</div>
		<div class="lg:w-1/2">
			<p class="text-base text-gray-700 md:text-lg">
				For those who have seen the Earth from space, and for the hundreds and perhaps thousands
				more who will, the experience most certainly changes your perspective.
			</p>
		</div>
	</div>
	<div class="grid gap-8 row-gap-10 sm:grid-cols-2 lg:grid-cols-4">
		<div>
			<div class="flex items-center justify-center w-16 h-16 mb-4 rounded-full bg-indigo-50">
				<svg
					class="w-7 h-7 text-deep-purple-accent-400"
					stroke-linecap="round"
					stroke-width="2"
					viewBox="0 0 24 24"
				>
					<circle cx="11" cy="13" fill="none" r="9" stroke="currentColor" />
					<path
						d=" M21.955,18.005c1.089,2.145,1.378,3.816,0.622,4.572C20.92,24.234,14.799,20.799,9,15S-0.234,3.08,1.423,1.423 C2.18,0.666,3.853,0.956,6,2.047"
						stroke="currentColor"
						fill="none"
					/>
				</svg>
			</div>
			<h6 class="mb-2 font-semibold leading-5">Our planet</h6>
			<p class="mb-3 text-sm text-gray-900">
				We choose to go to the moon, not because it's easy, but because it's hard.
			</p>
			<ul class="mb-4 -ml-1 space-y-2">
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Earth
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Space
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Humans
				</li>
			</ul>
			<a
				href="/"
				aria-label=""
				class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
				>Learn more</a
			>
		</div>
		<div>
			<div class="flex items-center justify-center w-16 h-16 mb-4 rounded-full bg-indigo-50">
				<svg class="w-7 h-7 text-deep-purple-accent-400" viewBox="0 0 24 24" stroke-linecap="round">
					<path
						d="M2,10C2,5.029,6.47,1,12,1c5.379,0,10,4.029,10,9S15.712,23,12,23C8.212,23,2,14.971,2,10Z"
						fill="none"
						stroke-width="2"
						stroke="currentColor"
					/>
					<path
						d="M5,9a6.529,6.529,0,0,1,4.393,1.607C10.705,11.92,10,15,10,15a6.59,6.59,0,0,1-3.436-1.564C5.022,11.894,5,9,5,9Z"
						fill="none"
						stroke-width="1.5"
						stroke="currentColor"
					/>
					<path
						d="M19,9a6.523,6.523,0,0,0-4.392,1.608C13.3,11.92,14,15,14,15a6.59,6.59,0,0,0,3.436-1.564C18.978,11.894,19,9,19,9Z"
						fill="none"
						stroke-width="1.5"
						stroke="currentColor"
					/>
				</svg>
			</div>
			<h6 class="mb-2 font-semibold leading-5">Another life</h6>
			<p class="mb-3 text-sm text-gray-900">
				There can be no thought of finishing for "aiming for the stars".
			</p>
			<ul class="mb-4 -ml-1 space-y-2">
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Life
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Aliens
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Shrek
				</li>
			</ul>
			<a
				href="/"
				aria-label=""
				class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
				>Learn more</a
			>
		</div>
		<div>
			<div class="flex items-center justify-center w-16 h-16 mb-4 rounded-full bg-indigo-50">
				<svg
					class="w-7 h-7 text-deep-purple-accent-400"
					stroke-linecap="round"
					stroke-width="2"
					viewBox="0 0 24 24"
				>
					<path
						d="M8.291,18.709,4.182,22.818c-.419.419-1.43.086-2.258-.742s-1.161-1.839-.742-2.258l4.11-4.11"
						fill="none"
						stroke="currentColor"
					/>
					<ellipse
						cx="19.078"
						cy="4.922"
						fill="none"
						rx="2.5"
						ry="4.95"
						stroke="currentColor"
						transform="translate(2.107 14.932) rotate(-45)"
					/>
					<path
						d="M9.185,9.815,5.3,13.7c-.7.7-.143,2.382,1.238,3.762S9.6,19.4,10.3,18.7l3.885-3.885"
						fill="none"
						stroke="currentColor"
					/>
					<path
						d="M15.578,1.422,9.422,7.578c-.976.976-.2,3.335,1.732,5.268s4.292,2.708,5.268,1.732l6.156-6.156"
						fill="none"
						stroke="currentColor"
					/>
				</svg>
			</div>
			<h6 class="mb-2 font-semibold leading-5">Explore space</h6>
			<p class="mb-3 text-sm text-gray-900">
				We are all connected to the universe atomically, strong bonds.
			</p>
			<ul class="mb-4 -ml-1 space-y-2">
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Infinity
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Stars
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Black Holes
				</li>
			</ul>
			<a
				href="/"
				aria-label=""
				class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
				>Learn more</a
			>
		</div>
		<div>
			<div class="flex items-center justify-center w-16 h-16 mb-4 rounded-full bg-indigo-50">
				<svg
					class="w-7 h-7 text-deep-purple-accent-400"
					stroke-linecap="round"
					stroke-width="2"
					viewBox="0 0 24 24"
				>
					<path
						d="M8,13l3,3,9.379-9.379a2.122,2.122,0,0,0,0-3h0a2.122,2.122,0,0,0-3,0Z"
						fill="none"
						stroke="currentColor"
					/>
					<polyline fill="none" points="10 11 10 6 6 2 3 5 7 9" stroke="currentColor" />
					<polyline fill="none" points="15 12 15 17 19 21 22 18 18 14" stroke="currentColor" />
					<path d="M8,23a7,7,0,0,1-7-7" fill="none" stroke="currentColor" />
					<path d="M8,19a3,3,0,0,1-3-3" fill="none" stroke="currentColor" />
				</svg>
			</div>
			<h6 class="mb-2 font-semibold leading-5">First contact</h6>
			<p class="mb-3 text-sm text-gray-900">
				For those who have seen the Earth from space or in dreams.
			</p>
			<ul class="mb-4 -ml-1 space-y-2">
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Listen
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Communicate
				</li>
				<li class="flex items-start">
					<span class="mr-1">
						<svg
							class="w-5 h-5 mt-px text-deep-purple-accent-400"
							stroke="currentColor"
							viewBox="0 0 52 52"
						>
							<polygon
								stroke-width="4"
								stroke-linecap="round"
								stroke-linejoin="round"
								fill="none"
								points="29 13 14 29 25 29 23 39 38 23 27 23"
							/>
						</svg>
					</span>
					Run
				</li>
			</ul>
			<a
				href="/"
				aria-label=""
				class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
				>Learn more</a
			>
		</div>
	</div>
</div>

<div
	class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div class="flex flex-col mb-6 lg:justify-between lg:flex-row md:mb-8">
		<h2
			class="max-w-lg mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none md:mb-6 group"
		>
			<span class="inline-block mb-1 sm:mb-4">
				There is no must in art<br class="hidden md:block" />
				because art is free.
			</span>
			<div
				class="h-1 ml-auto duration-300 origin-left transform bg-deep-purple-accent-400 scale-x-30 group-hover:scale-x-100"
			/>
		</h2>
		<p class="text-gray-700 lg:text-sm lg:max-w-md">
			"Class is dead", says Foucault; however, according to Reicher, it is not so much class that is
			dead, but rather the absurdity, and some would say the paradigm, of class. However, the
			subject is interpolated into a postpatriarchialist dialectic theory that includes
			consciousness as a totality.
		</p>
	</div>
	<div class="grid gap-6 row-gap-5 mb-8 lg:grid-cols-4 sm:row-gap-6 sm:grid-cols-2">
		<a href="/" aria-label="View Item">
			<div
				class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl"
			>
				<img
					class="object-cover w-full h-56 md:h-64 xl:h-80"
					src="https://images.pexels.com/photos/3184311/pexels-photo-3184311.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;w=500"
					alt=""
				/>
				<div
					class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100"
				>
					<p class="mb-4 text-lg font-bold text-gray-100">Mona Lisa</p>
					<p class="text-sm tracking-wide text-gray-300">
						Painted between 1503 and 1517, Da Vinci’s alluring portrait has been dogged by two
						questions since the day it was made: Who’s the subject and why is she smiling?
					</p>
				</div>
			</div>
		</a>
		<a href="/" aria-label="View Item">
			<div
				class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl"
			>
				<img
					class="object-cover w-full h-56 md:h-64 xl:h-80"
					src="https://images.pexels.com/photos/3184338/pexels-photo-3184338.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
					alt=""
				/>
				<div
					class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100"
				>
					<p class="mb-4 text-lg font-bold text-gray-100">The Starry Night</p>
					<p class="text-sm tracking-wide text-gray-300">
						Vincent Van Gogh’s most popular painting, The Starry Night was created by Van Gogh at
						the asylum in Saint-Rémy, where he’d committed himself in 1889.
					</p>
				</div>
			</div>
		</a>
		<a href="/" aria-label="View Item">
			<div
				class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl"
			>
				<img
					class="object-cover w-full h-56 md:h-64 xl:h-80"
					src="https://images.pexels.com/photos/3184339/pexels-photo-3184339.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
					alt=""
				/>
				<div
					class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100"
				>
					<p class="mb-4 text-lg font-bold text-gray-100">The Kiss</p>
					<p class="text-sm tracking-wide text-gray-300">
						Opulently gilded and extravagantly patterned, The Kiss, Gustav Klimt’s fin-de-siècle
						portrayal of intimacy, is a mix of Symbolism and Vienna Jugendstil, the Austrian variant
						of Art Nouveau.
					</p>
				</div>
			</div>
		</a>
		<a href="/" aria-label="View Item">
			<div
				class="relative overflow-hidden transition duration-200 transform rounded shadow-lg hover:-translate-y-2 hover:shadow-2xl"
			>
				<img
					class="object-cover w-full h-56 md:h-64 xl:h-80"
					src="https://images.pexels.com/photos/3184360/pexels-photo-3184360.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
					alt=""
				/>
				<div
					class="absolute inset-0 px-6 py-4 transition-opacity duration-200 bg-black bg-opacity-75 opacity-0 hover:opacity-100"
				>
					<p class="mb-4 text-lg font-bold text-gray-100">The Harvesters</p>
					<p class="text-sm tracking-wide text-gray-300">
						Bruegel’s fanfare for the common man is considered one of the defining works of Western
						art. This composition was one of six created on the theme of the seasons.
					</p>
				</div>
			</div>
		</a>
	</div>
	<div class="text-center">
		<a
			href="/"
			aria-label=""
			class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
		>
			View gallery
			<svg class="inline-block w-3 ml-2" fill="currentColor" viewBox="0 0 12 12">
				<path
					d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"
				/>
			</svg>
		</a>
	</div>
</div>

<div
	class="relative px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div
		class="absolute inset-x-0 top-0 items-center justify-center hidden overflow-hidden md:flex md:inset-y-0"
	>
		<svg viewBox="0 0 88 88" class="w-full max-w-screen-xl text-indigo-100">
			<circle fill="currentColor" cx="44" cy="44" r="15.5" />
			<circle fill-opacity="0.2" fill="currentColor" cx="44" cy="44" r="44" />
			<circle fill-opacity="0.2" fill="currentColor" cx="44" cy="44" r="37.5" />
			<circle fill-opacity="0.3" fill="currentColor" cx="44" cy="44" r="29.5" />
			<circle fill-opacity="0.3" fill="currentColor" cx="44" cy="44" r="22.5" />
		</svg>
	</div>
	<div class="relative grid gap-5 sm:grid-cols-2 lg:grid-cols-4">
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Football Sports</p>
				<p class="text-sm leading-5 text-gray-900">
					Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing
					elit.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Bowling Sports</p>
				<p class="text-sm leading-5 text-gray-900">
					Disrupt inspire and think tank, social entrepreneur but preliminary thinking think tank
					compelling.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Cycling Sports</p>
				<p class="text-sm leading-5 text-gray-900">
					A slice of heaven. O for awesome, this chocka full cuzzie is as rip-off as a cracker.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Weight Lifting Sports</p>
				<p class="text-sm leading-5 text-gray-900">
					Meanwhile, in behind the bicycle shed, Hercules Morse, as big as a horse.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Golf Sports</p>
				<p class="text-sm leading-5 text-gray-900">
					Disrupt inspire and think tank, social entrepreneur but preliminary thinking think tank
					compelling.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Hockey Sports</p>
				<p class="text-sm leading-5 text-gray-900">
					A business big enough that it could be listed on the NASDAQ goes belly up.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Shooting Sports</p>
				<p class="text-sm leading-5 text-gray-900">
					Lookout flogging bilge rat main sheet bilge water nipper fluke to go on account heave down
					clap of thunder.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
		<div
			class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-white rounded shadow-xl group hover:shadow-2xl"
		>
			<div class="p-5">
				<div class="flex items-center justify-center w-10 h-10 mb-4 rounded-full bg-indigo-50">
					<svg
						class="w-8 h-8 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
				<p class="mb-2 font-bold">Martial Arts</p>
				<p class="text-sm leading-5 text-gray-900">
					Webtwo ipsum orkut reddit meebo skype vimeo jajah spock empressr zimbra, mobly napster.
				</p>
			</div>
			<div
				class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"
			/>
		</div>
	</div>
</div>

<div
	class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div class="grid gap-5 row-gap-8 lg:grid-cols-2">
		<div class="flex flex-col justify-center">
			<div class="max-w-xl mb-6">
				<h2
					class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none"
				>
					The quick, brown fox<br class="hidden md:block" />
					jumps over
					<span class="relative px-1">
						<div class="absolute inset-x-0 bottom-0 h-3 transform -skew-x-12 bg-teal-accent-400" />
						<span class="relative inline-block text-deep-purple-accent-400">a lazy dog</span>
					</span>
				</h2>
				<p class="text-base text-gray-700 md:text-lg">
					Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
					laudantium, totam rem aperiam, eaque ipsa quae. explicabo.
				</p>
			</div>
			<div class="grid gap-5 row-gap-8 sm:grid-cols-2">
				<div class="bg-white border-l-4 shadow-sm border-deep-purple-accent-400">
					<div class="h-full p-5 border border-l-0 rounded-r">
						<h6 class="mb-2 font-semibold leading-5">I'll be sure to note that in my log</h6>
						<p class="text-sm text-gray-900">
							Lookout flogging bilge rat main sheet bilge water nipper fluke to go on account heave
							down.
						</p>
					</div>
				</div>
				<div class="bg-white border-l-4 shadow-sm border-deep-purple-accent-400">
					<div class="h-full p-5 border border-l-0 rounded-r">
						<h6 class="mb-2 font-semibold leading-5">
							A business big enough that it could be listed
						</h6>
						<p class="text-sm text-gray-900">
							Those options are already baked in with this model shoot me an email clear.
						</p>
					</div>
				</div>
			</div>
		</div>
		<div>
			<img
				class="object-cover w-full h-56 rounded shadow-lg sm:h-96"
				src="https://images.pexels.com/photos/927022/pexels-photo-927022.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=3&amp;h=750&amp;w=1260"
				alt=""
			/>
		</div>
	</div>
</div>

<div
	class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
		<div>
			<p
				class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400"
			>
				Our Pricing
			</p>
		</div>
		<h2
			class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto"
		>
			<span class="relative inline-block">
				<svg
					viewBox="0 0 52 24"
					fill="currentColor"
					class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block"
				>
					<defs>
						<pattern
							id="7e5e8ff8-1960-4094-a63a-2a0c0f922d69"
							x="0"
							y="0"
							width=".135"
							height=".30"
						>
							<circle cx="1" cy="1" r=".7" />
						</pattern>
					</defs>
					<rect fill="url(#7e5e8ff8-1960-4094-a63a-2a0c0f922d69)" width="52" height="24" />
				</svg>
				<span class="relative">Transparent</span>
			</span>
			pricing. Pay as you grow.
		</h2>
		<p class="text-base text-gray-700 md:text-lg">
			Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem
			aperiam, eaque ipsa quae.
		</p>
	</div>
	<div
		class="grid max-w-md gap-10 row-gap-5 lg:max-w-screen-lg sm:row-gap-10 lg:grid-cols-3 xl:max-w-screen-lg sm:mx-auto"
	>
		<div
			class="flex flex-col justify-between p-8 transition-shadow duration-300 bg-white border rounded shadow-sm sm:items-center hover:shadow"
		>
			<div class="text-center">
				<div class="text-lg font-semibold">Start</div>
				<div class="flex items-center justify-center mt-2">
					<div class="mr-1 text-5xl font-bold">Free</div>
				</div>
				<div class="mt-2 space-y-3">
					<div class="text-gray-700">10 deploys per day</div>
					<div class="text-gray-700">10 GB of storage</div>
					<div class="text-gray-700">20 domains</div>
				</div>
			</div>
			<div>
				<a
					href="/"
					class="inline-flex items-center justify-center w-full h-12 px-6 mt-6 font-medium tracking-wide text-white transition duration-200 bg-gray-800 rounded shadow-md hover:bg-gray-900 focus:shadow-outline focus:outline-none"
				>
					Start for free
				</a>
				<p
					class="max-w-xs mt-6 text-xs text-gray-600 sm:text-sm sm:text-center sm:max-w-sm sm:mx-auto"
				>
					Sed ut unde omnis iste natus accusantium doloremque.
				</p>
			</div>
		</div>
		<div
			class="relative flex flex-col justify-between p-8 transition-shadow duration-300 bg-white border rounded shadow-sm sm:items-center hover:shadow border-deep-purple-accent-400"
		>
			<div class="absolute inset-x-0 top-0 flex justify-center -mt-3">
				<div
					class="inline-block px-3 py-1 text-xs font-medium tracking-wider text-white uppercase rounded bg-deep-purple-accent-400"
				>
					Most Popular
				</div>
			</div>
			<div class="text-center">
				<div class="text-lg font-semibold">Pro</div>
				<div class="flex items-center justify-center mt-2">
					<div class="mr-1 text-5xl font-bold">$38</div>
					<div class="text-gray-700">/ mo</div>
				</div>
				<div class="mt-2 space-y-3">
					<div class="text-gray-700">200 deploys per day</div>
					<div class="text-gray-700">80 GB of storage</div>
					<div class="text-gray-700">Global CDN</div>
				</div>
			</div>
			<div>
				<a
					href="/"
					class="inline-flex items-center justify-center w-full h-12 px-6 mt-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
				>
					Buy Pro
				</a>
				<p
					class="max-w-xs mt-6 text-xs text-gray-600 sm:text-sm sm:text-center sm:max-w-sm sm:mx-auto"
				>
					Sed ut unde omnis iste natus accusantium doloremque.
				</p>
			</div>
		</div>
		<div
			class="flex flex-col justify-between p-8 transition-shadow duration-300 bg-white border rounded shadow-sm sm:items-center hover:shadow"
		>
			<div class="text-center">
				<div class="text-lg font-semibold">Business</div>
				<div class="flex items-center justify-center mt-2">
					<div class="mr-1 text-5xl font-bold">$78</div>
					<div class="text-gray-700">/ mo</div>
				</div>
				<div class="mt-2 space-y-3">
					<div class="text-gray-700">500 GB of storage</div>
					<div class="text-gray-700">Unlimited domains</div>
					<div class="text-gray-700">24/7 Support</div>
				</div>
			</div>
			<div>
				<a
					href="/"
					class="inline-flex items-center justify-center w-full h-12 px-6 mt-6 font-medium tracking-wide text-white transition duration-200 bg-gray-800 rounded shadow-md hover:bg-gray-900 focus:shadow-outline focus:outline-none"
				>
					Buy Business
				</a>
				<p
					class="max-w-xs mt-6 text-xs text-gray-600 sm:text-sm sm:text-center sm:max-w-sm sm:mx-auto"
				>
					Sed ut unde omnis iste natus accusantium doloremque.
				</p>
			</div>
		</div>
	</div>
</div>

<div
	class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
		<div>
			<p
				class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400"
			>
				Brand new
			</p>
		</div>
		<h2
			class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto"
		>
			<span class="relative inline-block">
				<svg
					viewBox="0 0 52 24"
					fill="currentColor"
					class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block"
				>
					<defs>
						<pattern
							id="bc9273ce-29bb-4565-959b-714607d4d027"
							x="0"
							y="0"
							width=".135"
							height=".30"
						>
							<circle cx="1" cy="1" r=".7" />
						</pattern>
					</defs>
					<rect fill="url(#bc9273ce-29bb-4565-959b-714607d4d027)" width="52" height="24" />
				</svg>
				<span class="relative">Choose</span>
			</span>
			your way. Advance everyday.
		</h2>
		<p class="text-base text-gray-700 md:text-lg">
			Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem
			aperiam, eaque ipsa quae.
		</p>
	</div>
	<div
		class="grid max-w-md gap-10 row-gap-8 lg:max-w-screen-lg sm:row-gap-10 lg:grid-cols-3 xl:max-w-screen-lg sm:mx-auto"
	>
		<div class="flex flex-col transition duration-300 bg-white rounded shadow-sm hover:shadow">
			<div class="relative w-full h-48">
				<img
					src="https://images.pexels.com/photos/3184305/pexels-photo-3184305.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
					class="object-cover w-full h-full rounded-t"
					alt="Plan"
				/>
			</div>
			<div class="flex flex-col justify-between flex-grow p-8 border border-t-0 rounded-b">
				<div>
					<div class="text-lg font-semibold">Basic</div>
					<p class="text-sm text-gray-900">
						Sed ut perspiciatis unde omnis iste natus error sit voluptatem doloremque.
					</p>
					<div class="mt-1 mb-4 mr-1 text-4xl font-bold sm:text-5xl">$12</div>
				</div>
				<a
					href="/"
					class="inline-flex items-center justify-center w-full h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
				>
					Buy Basic
				</a>
			</div>
		</div>
		<div class="flex flex-col transition duration-300 bg-white rounded shadow-sm hover:shadow">
			<div class="relative w-full h-48">
				<img
					src="https://images.pexels.com/photos/3183181/pexels-photo-3183181.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
					class="object-cover w-full h-full rounded-t"
					alt="Plan"
				/>
			</div>
			<div class="flex flex-col justify-between flex-grow p-8 border border-t-0 rounded-b">
				<div>
					<div class="text-lg font-semibold">Advanced</div>
					<p class="text-sm text-gray-900">
						A flower in my garden, a mystery in my panties. Heart attack never was so close.
					</p>
					<div class="mt-1 mb-4 mr-1 text-4xl font-bold sm:text-5xl">$38</div>
				</div>
				<a
					href="/"
					class="inline-flex items-center justify-center w-full h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
				>
					Buy Advanced
				</a>
			</div>
		</div>
		<div class="flex flex-col transition duration-300 bg-white rounded shadow-sm hover:shadow">
			<div class="relative w-full h-48">
				<img
					src="https://images.pexels.com/photos/3182743/pexels-photo-3182743.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
					class="object-cover w-full h-full rounded-t"
					alt="Plan"
				/>
			</div>
			<div class="flex flex-col justify-between flex-grow p-8 border border-t-0 rounded-b">
				<div>
					<div class="text-lg font-semibold">Pro</div>
					<p class="text-sm text-gray-900">
						We never had the chance to. Maybe it was the eleven months he spent in the womb.
					</p>
					<div class="mt-1 mb-4 mr-1 text-4xl font-bold sm:text-5xl">$78</div>
				</div>
				<a
					href="/"
					class="inline-flex items-center justify-center w-full h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
				>
					Buy Pro
				</a>
			</div>
		</div>
	</div>
</div>

<div
	class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div class="max-w-xl sm:mx-auto lg:max-w-2xl">
		<div class="flex flex-col mb-16 sm:text-center">
			<a href="/" class="mb-6 sm:mx-auto">
				<div class="flex items-center justify-center w-12 h-12 rounded-full bg-indigo-50">
					<svg
						class="w-10 h-10 text-deep-purple-accent-400"
						stroke="currentColor"
						viewBox="0 0 52 52"
					>
						<polygon
							stroke-width="3"
							stroke-linecap="round"
							stroke-linejoin="round"
							fill="none"
							points="29 13 14 29 25 29 23 39 38 23 27 23"
						/>
					</svg>
				</div>
			</a>
			<div class="max-w-xl md:mx-auto sm:text-center lg:max-w-2xl">
				<h2
					class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto"
				>
					<span class="relative inline-block">
						<svg
							viewBox="0 0 52 24"
							fill="currentColor"
							class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block"
						>
							<defs>
								<pattern
									id="ec5d8ef5-b853-4714-b94f-df28ec98eeb7"
									x="0"
									y="0"
									width=".135"
									height=".30"><circle cx="1" cy="1" r=".7" /></pattern
								>
							</defs>
							<rect fill="url(#ec5d8ef5-b853-4714-b94f-df28ec98eeb7)" width="52" height="24" />
						</svg>
						<span class="relative">The</span>
					</span>
					quick, brown fox jumps over a lazy dog
				</h2>
				<p class="text-base text-gray-700 md:text-lg">
					Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem
					aperiam, eaque ipsa quae.
				</p>
			</div>
		</div>
		<div class="space-y-4">
			<div class="border rounded shadow-sm">
				<button
					type="button"
					aria-label="Open item"
					title="Open item"
					class="flex items-center justify-between w-full p-4 focus:outline-none"
				>
					<p class="text-lg font-medium">The quick, brown fox jumps over a lazy dog?</p>
					<div class="flex items-center justify-center w-8 h-8 border rounded-full">
						<!-- Add "transform rotate-180" classes on svg, if is open" -->
						<svg viewBox="0 0 24 24" class="w-3 text-gray-600 transition-transform duration-200">
							<polyline
								fill="none"
								stroke="currentColor"
								stroke-width="2"
								stroke-linecap="round"
								stroke-miterlimit="10"
								points="2,7 12,17 22,7"
								stroke-linejoin="round"
							/>
						</svg>
					</div>
				</button>
				<!-- Show content if is open 
          <div class="p-4 pt-0"><p class="text-gray-700">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem aperiam, eaque ipsa quae.</p></div>
          -->
			</div>
			<div class="border rounded shadow-sm">
				<button
					type="button"
					aria-label="Open item"
					title="Open item"
					class="flex items-center justify-between w-full p-4 focus:outline-none"
				>
					<p class="text-lg font-medium">The first mate and his Skipper too will do?</p>
					<div class="flex items-center justify-center w-8 h-8 border rounded-full">
						<svg
							viewBox="0 0 24 24"
							class="w-3 text-gray-600 transition-transform duration-200 transform rotate-180"
						>
							<polyline
								fill="none"
								stroke="currentColor"
								stroke-width="2"
								stroke-linecap="round"
								stroke-miterlimit="10"
								points="2,7 12,17 22,7"
								stroke-linejoin="round"
							/>
						</svg>
					</div>
				</button>
				<!-- Show content if is open 
          <div class="p-4 pt-0"><p class="text-gray-700">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem aperiam, eaque ipsa quae.</p></div>
          -->
			</div>
			<div class="border rounded shadow-sm">
				<button
					type="button"
					aria-label="Open item"
					title="Open item"
					class="flex items-center justify-between w-full p-4 focus:outline-none"
				>
					<p class="text-lg font-medium">Is the Space Pope reptilian!?</p>
					<div class="flex items-center justify-center w-8 h-8 border rounded-full">
						<svg
							viewBox="0 0 24 24"
							class="w-3 text-gray-600 transition-transform duration-200 transform rotate-180"
						>
							<polyline
								fill="none"
								stroke="currentColor"
								stroke-width="2"
								stroke-linecap="round"
								stroke-miterlimit="10"
								points="2,7 12,17 22,7"
								stroke-linejoin="round"
							/>
						</svg>
					</div>
				</button>
				<!-- Show content if is open 
          <div class="p-4 pt-0"><p class="text-gray-700">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem aperiam, eaque ipsa quae.</p></div>
          -->
			</div>
			<div class="border rounded shadow-sm">
				<button
					type="button"
					aria-label="Open item"
					title="Open item"
					class="flex items-center justify-between w-full p-4 focus:outline-none"
				>
					<p class="text-lg font-medium">How much money you got on you?</p>
					<div class="flex items-center justify-center w-8 h-8 border rounded-full">
						<svg
							viewBox="0 0 24 24"
							class="w-3 text-gray-600 transition-transform duration-200 transform rotate-180"
						>
							<polyline
								fill="none"
								stroke="currentColor"
								stroke-width="2"
								stroke-linecap="round"
								stroke-miterlimit="10"
								points="2,7 12,17 22,7"
								stroke-linejoin="round"
							/>
						</svg>
					</div>
				</button>
				<!-- Show content if is open
          <div class="p-4 pt-0"><p class="text-gray-700">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem aperiam, eaque ipsa quae.</p></div>
          -->
			</div>
		</div>
	</div>
</div>

<div
	class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
>
	<div class="grid gap-8 lg:grid-cols-3 sm:max-w-sm sm:mx-auto lg:max-w-full">
		<div class="overflow-hidden transition-shadow duration-300 bg-white rounded shadow-sm">
			<img
				src="https://images.pexels.com/photos/2408666/pexels-photo-2408666.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;w=500"
				class="object-cover w-full h-64"
				alt=""
			/>
			<div class="p-5 border border-t-0">
				<p class="mb-3 text-xs font-semibold tracking-wide uppercase">
					<a
						href="/"
						class="transition-colors duration-200 text-blue-gray-900 hover:text-deep-purple-accent-700"
						aria-label="Category"
						title="traveling">traveling</a
					>
					<span class="text-gray-600">— 28 Dec 2020</span>
				</p>
				<a
					href="/"
					aria-label="Category"
					title="Visit the East"
					class="inline-block mb-3 text-2xl font-bold leading-5 transition-colors duration-200 hover:text-deep-purple-accent-700"
					>Visit the East</a
				>
				<p class="mb-2 text-gray-700">
					Sed ut perspiciatis unde omnis iste natus error sit sed quia consequuntur magni voluptatem
					doloremque.
				</p>
				<a
					href="/"
					aria-label=""
					class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
					>Learn more</a
				>
			</div>
		</div>
		<div class="overflow-hidden transition-shadow duration-300 bg-white rounded shadow-sm">
			<img
				src="https://images.pexels.com/photos/447592/pexels-photo-447592.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
				class="object-cover w-full h-64"
				alt=""
			/>
			<div class="p-5 border border-t-0">
				<p class="mb-3 text-xs font-semibold tracking-wide uppercase">
					<a
						href="/"
						class="transition-colors duration-200 text-blue-gray-900 hover:text-deep-purple-accent-700"
						aria-label="Category"
						title="traveling">traveling</a
					>
					<span class="text-gray-600">— 28 Dec 2020</span>
				</p>
				<a
					href="/"
					aria-label="Category"
					title="Simple is better"
					class="inline-block mb-3 text-2xl font-bold leading-5 transition-colors duration-200 hover:text-deep-purple-accent-700"
					>Simple is better</a
				>
				<p class="mb-2 text-gray-700">
					Sed ut perspiciatis unde omnis iste natus error sit sed quia consequuntur magni voluptatem
					doloremque.
				</p>
				<a
					href="/"
					aria-label=""
					class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
					>Learn more</a
				>
			</div>
		</div>
		<div class="overflow-hidden transition-shadow duration-300 bg-white rounded shadow-sm">
			<img
				src="https://images.pexels.com/photos/139829/pexels-photo-139829.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
				class="object-cover w-full h-64"
				alt=""
			/>
			<div class="p-5 border border-t-0">
				<p class="mb-3 text-xs font-semibold tracking-wide uppercase">
					<a
						href="/"
						class="transition-colors duration-200 text-blue-gray-900 hover:text-deep-purple-accent-700"
						aria-label="Category"
						title="traveling">traveling</a
					>
					<span class="text-gray-600">— 28 Dec 2020</span>
				</p>
				<a
					href="/"
					aria-label="Category"
					title="Film It!"
					class="inline-block mb-3 text-2xl font-bold leading-5 transition-colors duration-200 hover:text-deep-purple-accent-700"
					>Film It!</a
				>
				<p class="mb-2 text-gray-700">
					Sed ut perspiciatis unde omnis iste natus error sit sed quia consequuntur magni voluptatem
					doloremque.
				</p>
				<a
					href="/"
					aria-label=""
					class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800"
					>Learn more</a
				>
			</div>
		</div>
	</div>
</div>

<div class="bg-gray-900">
	<div class="px-4 pt-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
		<div class="grid row-gap-10 mb-8 lg:grid-cols-6">
			<div class="grid grid-cols-2 gap-5 row-gap-8 lg:col-span-4 md:grid-cols-4">
				<div>
					<p class="font-medium tracking-wide text-gray-300">Category</p>
					<ul class="mt-2 space-y-2">
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>News</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>World</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Games</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>References</a
							>
						</li>
					</ul>
				</div>
				<div>
					<p class="font-medium tracking-wide text-gray-300">Apples</p>
					<ul class="mt-2 space-y-2">
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Web</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>eCommerce</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Business</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Entertainment</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Portfolio</a
							>
						</li>
					</ul>
				</div>
				<div>
					<p class="font-medium tracking-wide text-gray-300">Cherry</p>
					<ul class="mt-2 space-y-2">
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Media</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Brochure</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Nonprofit</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Educational</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Projects</a
							>
						</li>
					</ul>
				</div>
				<div>
					<p class="font-medium tracking-wide text-gray-300">Business</p>
					<ul class="mt-2 space-y-2">
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Infopreneur</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Personal</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Wiki</a
							>
						</li>
						<li>
							<a
								href="/"
								class="text-gray-500 transition-colors duration-300 hover:text-deep-purple-accent-200"
								>Forum</a
							>
						</li>
					</ul>
				</div>
			</div>
			<div class="md:max-w-md lg:col-span-2">
				<span class="text-base font-medium tracking-wide text-gray-300">Subscribe for updates</span>
				<form class="flex flex-col mt-4 md:flex-row">
					<input
						placeholder="Email"
						required=""
						type="text"
						class="flex-grow w-full h-12 px-4 mb-3 transition duration-200 bg-white border border-gray-300 rounded shadow-sm appearance-none md:mr-2 md:mb-0 focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline"
					/>
					<button
						type="submit"
						class="inline-flex items-center justify-center h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
					>
						Subscribe
					</button>
				</form>
				<p class="mt-4 text-sm text-gray-500">
					Bacon ipsum dolor amet short ribs pig sausage prosciuto chicken spare ribs salami.
				</p>
			</div>
		</div>
		<div class="flex flex-col justify-between pt-5 pb-10 border-t border-gray-800 sm:flex-row">
			<p class="text-sm text-gray-500">© Copyright 2020 Lorem Inc. All rights reserved.</p>
			<div class="flex items-center mt-4 space-x-4 sm:mt-0">
				<a href="/" class="text-gray-500 transition-colors duration-300 hover:text-teal-accent-400">
					<svg viewBox="0 0 24 24" fill="currentColor" class="h-5">
						<path
							d="M24,4.6c-0.9,0.4-1.8,0.7-2.8,0.8c1-0.6,1.8-1.6,2.2-2.7c-1,0.6-2,1-3.1,1.2c-0.9-1-2.2-1.6-3.6-1.6 c-2.7,0-4.9,2.2-4.9,4.9c0,0.4,0,0.8,0.1,1.1C7.7,8.1,4.1,6.1,1.7,3.1C1.2,3.9,1,4.7,1,5.6c0,1.7,0.9,3.2,2.2,4.1 C2.4,9.7,1.6,9.5,1,9.1c0,0,0,0,0,0.1c0,2.4,1.7,4.4,3.9,4.8c-0.4,0.1-0.8,0.2-1.3,0.2c-0.3,0-0.6,0-0.9-0.1c0.6,2,2.4,3.4,4.6,3.4 c-1.7,1.3-3.8,2.1-6.1,2.1c-0.4,0-0.8,0-1.2-0.1c2.2,1.4,4.8,2.2,7.5,2.2c9.1,0,14-7.5,14-14c0-0.2,0-0.4,0-0.6 C22.5,6.4,23.3,5.5,24,4.6z"
						/>
					</svg>
				</a>
				<a href="/" class="text-gray-500 transition-colors duration-300 hover:text-teal-accent-400">
					<svg viewBox="0 0 30 30" fill="currentColor" class="h-6">
						<circle cx="15" cy="15" r="4" />
						<path
							d="M19.999,3h-10C6.14,3,3,6.141,3,10.001v10C3,23.86,6.141,27,10.001,27h10C23.86,27,27,23.859,27,19.999v-10   C27,6.14,23.859,3,19.999,3z M15,21c-3.309,0-6-2.691-6-6s2.691-6,6-6s6,2.691,6,6S18.309,21,15,21z M22,9c-0.552,0-1-0.448-1-1   c0-0.552,0.448-1,1-1s1,0.448,1,1C23,8.552,22.552,9,22,9z"
						/>
					</svg>
				</a>
				<a href="/" class="text-gray-500 transition-colors duration-300 hover:text-teal-accent-400">
					<svg viewBox="0 0 24 24" fill="currentColor" class="h-5">
						<path
							d="M22,0H2C0.895,0,0,0.895,0,2v20c0,1.105,0.895,2,2,2h11v-9h-3v-4h3V8.413c0-3.1,1.893-4.788,4.659-4.788 c1.325,0,2.463,0.099,2.795,0.143v3.24l-1.918,0.001c-1.504,0-1.795,0.715-1.795,1.763V11h4.44l-1,4h-3.44v9H22c1.105,0,2-0.895,2-2 V2C24,0.895,23.105,0,22,0z"
						/>
					</svg>
				</a>
			</div>
		</div>
	</div>
</div>
