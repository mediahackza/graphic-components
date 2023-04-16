<script>
    export let title = '';
    export let description = '';
    export let canonical = '';
    export let robots = "index, follow";
    export let image = ''
    export let url = ''
    export let sitename = ''

</script>

<svelte:head>
<title>{title}</title>
<!-- Description: 150-160 characters -->
<meta name="description" content="{description}">
<!-- The Original Page is there are copies/duplicates -->
<link rel="canonical" href="{canonical}" />
<meta name=”robots” content="{robots}">
<!-- Open graph tags -->
<meta property="og:type" content="article" />
<meta property="og:title" content="{title}" />
<meta property="og:description" content="{description}" />
<meta property="og:image" content="{image}" />
<meta property="og:url" content="{url}" />
<meta property="og:site_name" content="{sitename}" />
<!-- Twitter Tags -->
<meta name="twitter:title" content="{title}">
<meta name="twitter:description" content="{description}">
<meta name="twitter:image" content="{image}">
<meta name="twitter:site" content="@outlierafrica">
<meta name="twitter:creator" content="@outlierafrica">
</svelte:head> 