<script lang="ts">
	import MenuBar from '$lib/MenuBar.svelte';
	import Window from '$lib/Window.svelte';
	import Copyright from '$lib/Copyright.svelte';
	import Skills from '$lib/Skills.svelte';
	import Experience from '$lib/Experience.svelte';
	import Contact from '$lib/Contact.svelte';
</script>

<MenuBar />
<div class="desktop">
	<section id="about">
		<Window title="About Me">
			<p>
				I am a DevOps Engineer at <a href="https://www.knoxsystems.com/" target="_blank"
					>Knox Systems</a
				> with 3+ years of experience architecting secure and scalable cloud infrastructure, and backend
				development.
			</p>
			<p>
				Outside of work I enjoy playing guitar, cooking, and rock climbing. I currently reside in
				Philadelphia, PA.
			</p>
			<p>
				Here's my <a href="https://www.adamattia.net/resume" target="_blank">resume</a>. (Last
				updated 06/2025)
			</p>
		</Window>
	</section>
	<section id="skills">
		<Window title="Skills">
			<Skills />
		</Window>
	</section>

	<section id="experience">
		<Window title="Experience ">
			<Experience />
		</Window>
	</section>

	<section id="contact">
		<Window title="Contact">
			<Contact />
		</Window>
	</section>

	<Copyright></Copyright>
</div>

<style>
	.desktop {
		padding: 60px 20px 20px 20px;
	}

	section {
		margin-bottom: 20px;
		scroll-margin-top: 100px;
	}
</style>
