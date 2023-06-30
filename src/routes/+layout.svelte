<script lang="ts">
	import '../app.css';
	import Header from './header.svelte';
</script>

<svelte:head>
	<title>High Performace Web Application Developer</title>
	<meta
		name="description"
		content="Hi. I am Augustine Madu, mostly known as Cudi. I am a software developer and I build high performance web applications. If you are in need of a web developer for your business application, or just for questions and collaborations, You can email me at partner@cudi.dev"
	/>
	<meta property="og:title" content="High Performace Web Application Developer" />
	<meta
		property="og:description"
		content="Hi. I am Augustine Madu, mostly known as Cudi. I am a software developer and I build high performance web applications. If you are in need of a web developer for your business application, or just for questions and collaborations, You can email me at partner@cudi.dev"
	/>
	<meta property="og:url" content="https://cudi.dev" />
	<meta property="og:type" content="website" />
	<meta property="og:locale" content="en_GB" />
	<meta property="og:image" content="https://cudi.dev/og-image.png" />
	<meta name="twitter:card" content="product" />
	<meta name="twitter:site" content="@CudiLala_" />
	<meta name="twitter:creator" content="@CudiLala_" />
	<meta name="twitter:title" content="High Performace Web Application Developer" />
	<meta
		name="twitter:description"
		content="Hi. I am Augustine Madu, mostly known as Cudi. I am a software developer and I build high performance web applications. If you are in need of a web developer for your business application, or just for questions and collaborations, You can email me at partner@cudi.dev"
	/>
	<meta property="twitter:url" content="https://cudi.dev" />
	<meta property="twitter:image" content="https://cudi.dev/og-image.png" />
</svelte:head>

<Header />
<slot />
