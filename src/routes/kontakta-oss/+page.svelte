
<svelte:head>
    <title>Kontakta oss för professionell bilvård i Karlstad - Boka tid idag</title>
    <meta name="description" content="Våra bilvårdstjänster garanterar en heltäckande och detaljerad bilvårdstjänst som garanterar en skinande ren och välskött bil. Kontakta oss idag för att boka tid och utforska mer om våra bilvårdstjänster.">
    <meta name="keywords" content="bilvård, professionell bilvård, bilvårdstjänster, Karlstad, boka tid">
</svelte:head>
<!-- Contact Section: Split -->
<div class="relative  flex items-center overflow-hidden">
	<div class="absolute top-0 right-0 bottom-0 w-full lg:w-1/2 " />
	<div class="relative container xl:max-w-7xl mx-auto px-4 py-16 lg:px-8 lg:py-32">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-0">
			<!-- Heading -->
			<div class="flex items-center lg:px-14 xl:px-28 space-y-6">
				<div class="w-full">
					<div class="text-sm uppercase font-bold tracking-wider mb-1 text-rose-700">
						Vi svarar inom kort
					</div>
					<h2 class="text-3xl md:text-4xl font-extrabold mb-4">Hör av Dig!</h2>
					<h3 class="text-lg md:text-xl md:leading-relaxed font-medium text-gray-500">
						Kontakta oss via telefon eller mejl för att boka tid eller få mer information om våra
						bilvårdstjänster. Vi finns tillgängliga för att hjälpa dig på bästa sätt.
					</h3>
					<h4 class="uppercase text-sm font-semibold tracking-wider mt-12 mb-2">
						Carglans i Karlstad AB
					</h4>
					<div class="leading-relaxed">
						Våxnäsgatan 150, Karlstad<br />
						Sverige, Värmland<br />
						<a href="tel:+46707875195">
						<abbr title="Phone">T:</abbr>
						(070)-787 51 95</a>
					</div>
					<a href="mailto:carglans@hotmail.com">
					<div class="leading-relaxed">
						<abbr title="Email">E:</abbr>
						carglans@hotmail.com
					</div>
				</a>
				</div>
			</div>
			<!-- END Heading -->

			<!-- Contact Form -->
			<div class="flex items-center lg:px-14 xl:px-20">
				<form name="contact" method="POST" data-netlify="true" class="space-y-6 w-full">
					<input type="hidden" name="form-name" value="contact" />
					<div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
						<div class="space-y-1">
							<label for="firstname" class="font-medium"
								>Förnamn
								<input
									class="block border placeholder-gray-490 px-5 bg-gray-900 py-3 leading-6 w-full rounded border-gray-200 focus:border-rose-500 focus:ring focus:ring-rose-500 focus:ring-opacity-50"
									type="text"
									name="Förnamn"
									id="name"
									required
									placeholder="Förnamn"
								/></label
							>
						</div>
						<div class="space-y-1">
							<label for="lastname" class="font-medium"
								>Efternamn
								<input
									class="block border placeholder-gray-400 px-5 py-3 bg-gray-900 leading-6 w-full rounded border-gray-200 focus:border-rose-500 focus:ring focus:ring-rose-500 focus:ring-opacity-50"
									type="text"
									name="Efternamn"
									id="name"
									required
									placeholder="Efternamn"
								/></label
							>
						</div>
					</div>
					<div class="space-y-1">
						<label for="email" class="font-medium"
							>Email
							<input
								class="block border placeholder-gray-400 px-5 py-3 bg-gray-900 leading-6 w-full rounded border-gray-200 focus:border-rose-500 focus:ring focus:ring-rose-500 focus:ring-opacity-50"
								type="email"
								name="email"
								id="email"
								required
								placeholder="Email"
							/></label
						>
					</div>
					<div class="space-y-1">
						<label for="message" class="font-medium"
							>Meddelande
							<textarea
								class="block border border-gray-200 rounded bg-gray-900 placeholder-gray-400 px-5 py-3 w-full focus:border-rose-500 focus:ring focus:ring-rose-500 focus:ring-opacity-50"
								name="Meddelande"
								id="message"
								required
								placeholder="Meddelande"
								rows="6"
							/></label
						>
					</div>
					<button
						type="submit"
						class="inline-flex justify-center items-center space-x-2 border font-semibold focus:outline-none px-3 py-2 leading-6 rounded border-rose-700 bg-rose-700 text-white hover:text-white hover:bg-rose-800 hover:border-rose-800 focus:ring focus:ring-rose-500 focus:ring-opacity-50 active:bg-rose-700 active:border-rose-700"
					>
						<svg
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							class="opacity-50 hi-solid hi-paper-airplane inline-block w-5 h-5"
							><path
								d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"
							/></svg
						>
						<span>Skicka Email</span>
					</button>
				</form>
			</div>
			<!-- END Contact Form -->
		</div>
	</div>
</div>
<!-- END Contact Section: Split -->
