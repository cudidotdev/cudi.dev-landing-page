<div class="relative">
	<div class="absolute -z-10 hidden lg:block top-0 left-0 w-1/2 h-full bg-custom-800" />
	<div class="absolute -z-10 hidden lg:block top-0 left-1/2 w-1/2 h-full bg-custom-900" />

	<div class="max-w-screen-xl mx-auto flex flex-col lg:flex-row justify-start items-stretch">
		<div class="bg-custom-800 lg:grow-0 lg:basis-[30rem] py-4">
			<h2 class="p-4 pt-8 sm:p-8 max-w-screen-xl mx-auto">
				<p class="text-4xl smc:text-5xl md:text-7xl text-custom-400">Socials</p>
			</h2>

			<div class="flex flex-col gap-4 px-5 sm:px-10 sm:[&>*]:text-xl py-4">
				<a target="_blank" href="https://github.com/CudiLala">GitHub</a>
				<a target="_blank" href="https://www.linkedin.com/in/augustine-madu-625168223/">LinkedIn</a>
				<a target="_blank" href="?">Youtube</a>
				<a target="_blank" href="https://github.com/CudiLala">Twitter</a>
				<a target="_blank" href="?">Instagram</a>
				<a target="_blank" href="?">Facebook</a>
			</div>
		</div>

		<div class="bg-custom-900 lg:grow py-4">
			<h2 class="p-4 pt-8 sm:p-8 max-w-screen-xl mx-auto">
				<p class="text-4xl smc:text-5xl md:text-7xl text-custom-400">Contact Me</p>
			</h2>

			<form
				class="flex flex-col gap-4 px-5 sm:px-10 smc:[&>*]:text-xl py-4"
				on:submit|preventDefault={() => {}}
			>
				<div class="gap-4 grid grid-cols-1 sm:grid-cols-2">
					<div class="flex flex-col gap-1">
						<input type="text" class="input peer" id="cfn" />
						<label for="cfn" class="label"> First Name </label>
					</div>

					<div class="flex flex-col gap-1">
						<input type="text" class="input peer" id="cln" />
						<label for="cln" class="label">Last Name</label>
					</div>
				</div>

				<div class="flex flex-col gap-1">
					<input type="email" class="input peer" id="cea" />
					<label for="cea" class="label">Email</label>
				</div>

				<div class="flex flex-col gap-1">
					<input type="text" class="input peer" id="cs" />
					<label for="cs" class="label">Subject</label>
				</div>

				<div class="flex flex-col gap-1">
					<textarea class="textarea peer" id="cb" />
					<label for="cb" class="label">Body</label>
				</div>

				<button type="submit" class="primary-btn">Send</button>
			</form>
		</div>
	</div>
</div>
