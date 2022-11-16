<template>
	<div>
		<header class="bg-teal-500 flex mx-auto justify-between p-4">
			<nav>
				<NuxtLink to="/">KeyWorld</NuxtLink>
				<ul>
					<li>
						<NuxtLink to="/about">About</NuxtLink>
					</li>
				</ul>
			</nav>
		</header>
		<div class="container mx-auto p-4">
			<slot />
		</div>
		<footer class="container mx-auto p-4 flex justify-between bottom-0 fixed">
			<p>Created by Ivan White | 2022</p>
		</footer>
	</div>
</template>

<style scoped>
	.router-link-exact-active {
		color: red;
	}
</style>
