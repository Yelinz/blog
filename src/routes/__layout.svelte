<script>
import Header from "$lib/header.svelte";

</script>

<svelte:head>
  <title>Welcome</title>
</svelte:head>

<Header></Header>

<main>
 <slot></slot>
</main>
