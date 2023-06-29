
<script>
	let step = 0;

	function add() {
		step++;
	}
</script>

<div class="container h-full mx-auto flex justify-center items-center">

	{#if step === 0}
		<div class="flex min-h-full flex-col justify-center px-6 py-12 lg:px-8">
			<div class="sm:mx-auto sm:w-full sm:max-w-sm">
			<img class="mx-auto h-10 w-auto" src="https://www.ucab.edu.ve/wp-content/uploads/2019/04/Logo_UCAB_3.png" alt="Your Company">
			<h2 class="mt-10 text-center text-2xl font-bold leading-9 tracking-tight text-gray-900">Bienvenido al Sistema de Elecciones</h2>
			</div>
			<div class="mt-10 sm:mx-auto sm:w-full sm:max-w-sm">
				<div>
					<button on:click={add} class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Acceder</button>
				</div>
				<p class="mt-10 text-center text-sm text-gray-500">
					No posees una cuenta?
					<a href="https://www.ucab.edu.ve/cuentadeusuario/" class="font-semibold leading-6 text-indigo-600 hover:text-indigo-500">Crear Usuario</a>
				</p>
			</div>
		</div>
	{/if}

	{#if step === 1}
		<div class="">
			<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
				<div class="mx-auto max-w-2xl py-12 sm:py-16 lg:max-w-none lg:py-24">
					<div class="mt-6 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 lg:grid-cols-4 xl:gap-x-8">
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-01.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-02.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-03.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-01.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-02.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-03.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-01.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-02.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-03.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-01.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-02.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
						<div class="group relative" on:click={add}>
							<div class="relative h-80 w-full overflow-hidden rounded-lg bg-white sm:aspect-h-1 sm:aspect-w-2 lg:aspect-h-1 lg:aspect-w-1 group-hover:opacity-75 sm:h-64">
							<img src="https://tailwindui.com/img/ecommerce-images/home-page-02-edition-03.jpg" alt="" class="h-full w-full object-cover object-center">
							</div>
							<h3 class="mt-6 text-sm text-gray-500">
							<a href="#">
								<span class="absolute inset-0"></span>
								Lorem ipsum
							</a>
							</h3>
							<p class="text-base font-semibold text-gray-900">Lorem ipsum</p>
						</div>
					</div>

					<div class="flex justify-center items-center">
						<div class="flex flex-col items-center w-full max-w-screen-md p-6 pb-6 mt-24 bg-white rounded-lg shadow-xl sm:p-8">
							<h2 class="text-xl font-bold">Participación</h2>
							<span class="text-sm font-semibold text-gray-500">2023</span>
							<div class="flex items-end flex-grow w-full mt-2 space-x-2 sm:space-x-3">
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">234</span>
									<div class="relative flex justify-center w-full h-8 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-6 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-16 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">645</span>
									<div class="relative flex justify-center w-full h-10 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-6 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-20 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">352</span>
									<div class="relative flex justify-center w-full h-10 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-8 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-20 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">324</span>
									<div class="relative flex justify-center w-full h-10 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-6 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-24 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">876</span>
									<div class="relative flex justify-center w-full h-10 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-8 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-20 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">785</span>
									<div class="relative flex justify-center w-full h-12 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-8 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-24 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">584</span>
									<div class="relative flex justify-center w-full h-12 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-16 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-20 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">365</span>
									<div class="relative flex justify-center w-full h-12 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-10 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-24 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">324</span>
									<div class="relative flex justify-center w-full h-12 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-10 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-32 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">274</span>
									<div class="relative flex justify-center w-full h-12 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-12 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full bg-indigo-400 h-28"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">358</span>
									<div class="relative flex justify-center w-full h-8 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-8 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-40 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
								<div class="relative flex flex-col items-center flex-grow pb-5 group">
									<span class="absolute top-0 hidden -mt-6 text-xs font-bold group-hover:block">952</span>
									<div class="relative flex justify-center w-full h-12 bg-indigo-200"></div>
									<div class="relative flex justify-center w-full h-8 bg-indigo-300"></div>
									<div class="relative flex justify-center w-full h-40 bg-indigo-400"></div>
									<span class="absolute bottom-0 text-xs font-bold">Escuela</span>
								</div>
							</div>
							<div class="flex w-full mt-3">
								<div class="flex items-center ml-auto">
									<span class="block w-4 h-4 bg-indigo-400"></span>
									<span class="ml-1 text-xs font-medium">Lorem ipsum</span>
								</div>
								<div class="flex items-center ml-4">
									<span class="block w-4 h-4 bg-indigo-300"></span>
									<span class="ml-1 text-xs font-medium">Lorem ipsum</span>
								</div>
								<div class="flex items-center ml-4">
									<span class="block w-4 h-4 bg-indigo-200"></span>
									<span class="ml-1 text-xs font-medium">Lorem ipsum</span>
								</div>
							</div>
						</div>
					</div>

					<div class="py-24 sm:py-32">
						<div class="mx-auto max-w-7xl px-6 lg:px-8">
							<dl class="grid grid-cols-1 gap-x-8 gap-y-16 text-center lg:grid-cols-3">
								<div class="mx-auto flex max-w-xs flex-col gap-y-4">
								<dt class="text-base leading-7 text-gray-600">Porcentaje de Participación</dt>
								<dd class="order-first text-3xl font-semibold tracking-tight text-gray-900 sm:text-5xl">40%</dd>
								</div>
								<div class="mx-auto flex max-w-xs flex-col gap-y-4">
								<dt class="text-base leading-7 text-gray-600">Número de Votos</dt>
								<dd class="order-first text-3xl font-semibold tracking-tight text-gray-900 sm:text-5xl">745</dd>
								</div>
								<div class="mx-auto flex max-w-xs flex-col gap-y-4">
								<dt class="text-base leading-7 text-gray-600">Participación en Escuela</dt>
								<dd class="order-first text-3xl font-semibold tracking-tight text-gray-900 sm:text-5xl">154</dd>
								</div>
							</dl>
						</div>
					</div>
				</div>
			</div>
		</div>
	{/if}

	{#if step === 2}
		<div class="">
			<div class="">
				<div class="">
					<div class="mt-6 grid grid-cols-1 gap-x-6 gap-y-10 lg:grid-cols-2 xl:gap-x-20">
						<div class="group relative">
							<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Candidatura 1</h3>
							<ul role="list" class="divide-y divide-gray-100">
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox" checked>
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
							</ul>
							<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Candidatura 2</h3>
							<ul role="list" class="divide-y divide-gray-100">
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox" checked>
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
							</ul>
						</div>
						<div class="group relative">
							<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Candidatura 3</h3>
							<ul role="list" class="divide-y divide-gray-100">
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox" checked>
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
							</ul>
							<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Candidatura 4</h3>
							<ul role="list" class="divide-y divide-gray-100">
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
								<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
									<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
									<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
								</div>
								<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox" checked>
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
								<li class="flex justify-between gap-x-6 py-5">
									<div class="flex gap-x-4">
									<img class="h-12 w-12 flex-none rounded-full bg-gray-50" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
									<div class="min-w-0 flex-auto">
										<p class="text-sm font-semibold leading-6 text-gray-900">Candidato</p>
										<p class="mt-1 truncate text-xs leading-5 text-gray-500">candidato@example.com</p>
									</div>
									</div>
									<div class="flex flex-col items-end">
									<p class="text-sm leading-6 text-gray-900">Partido / Puesto</p>
									<p class="mt-1 text-xs leading-5 text-gray-500">Lorem ipsum</p>
								</div>
								<div class="flex flex-col items-center justify-center">
									<input type="checkbox">
								</div>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
			<div class="flex w-full justify-center my-24">
				<button on:click={add} class="flex w-6/12 justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Continuar</button>
			</div>
		</div>
	{/if}

	{#if step === 3}
		<div class="py-24 sm:py-32">
			<div class="mx-auto grid max-w-7xl gap-x-8 gap-y-20 px-6 lg:px-8 xl:grid-cols-3">
			<div class="max-w-2xl">
				<h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Resumen de Selección</h2>
				<p class="mt-6 text-lg leading-8 text-gray-600">Verifica que tu selección este correcta y luego presiona el botón votar</p>
			</div>
			<ul role="list" class="grid gap-x-8 gap-y-12 sm:grid-cols-2 sm:gap-y-16 xl:col-span-2">
				<li>
				<div class="flex items-center gap-x-6">
					<img class="h-16 w-16 rounded-full" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
					<div>
					<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Nombre Candidato 1</h3>
					<p class="text-sm font-semibold leading-6 text-indigo-600">Partido / Puesto</p>
					</div>
				</div>
				</li>
				<li>
					<div class="flex items-center gap-x-6">
					<img class="h-16 w-16 rounded-full" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
					<div>
						<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Nombre Candidato  2</h3>
						<p class="text-sm font-semibold leading-6 text-indigo-600">Partido / Puesto</p>
					</div>
					</div>
				</li>
				<li>
					<div class="flex items-center gap-x-6">
					<img class="h-16 w-16 rounded-full" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
					<div>
						<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Nombre Candidato 3</h3>
						<p class="text-sm font-semibold leading-6 text-indigo-600">Partido / Puesto</p>
					</div>
					</div>
				</li>
				<li>
					<div class="flex items-center gap-x-6">
					<img class="h-16 w-16 rounded-full" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
					<div>
						<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Nombre Candidato 4</h3>
						<p class="text-sm font-semibold leading-6 text-indigo-600">Partido / Puesto</p>
					</div>
					</div>
				</li>
				<li>
					<div class="flex items-center gap-x-6">
					<img class="h-16 w-16 rounded-full" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
					<div>
						<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Nombre Candidato 5</h3>
						<p class="text-sm font-semibold leading-6 text-indigo-600">Partido / Puesto</p>
					</div>
					</div>
				</li>
				<li>
					<div class="flex items-center gap-x-6">
					<img class="h-16 w-16 rounded-full" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
					<div>
						<h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">Nombre Candidato  6</h3>
						<p class="text-sm font-semibold leading-6 text-indigo-600">Partido / Puesto</p>
					</div>
					</div>
				</li> 
			</ul>
			</div>
			<div class="flex w-full justify-center mt-24">
				<button type="submit" class="flex w-6/12 justify-center rounded-md bg-green-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-green-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-green-600">Votar</button>
			</div>
		</div>
	{/if}

</div>

<style lang="postcss">
	figure {
		@apply flex relative flex-col;
	}
	figure svg,
	.img-bg {
		@apply w-64 h-64 md:w-80 md:h-80;
	}
	.img-bg {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	@keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(1.5);
		}
	}
</style>
