<<<<<<< HEAD
<script>
    import CanvasSquare from "$lib/components/CanvasSquare.svelte";
=======
 <script>
>>>>>>> e88b783fd4a368a256a923453850371ab1148ccc
    import ClicksCounter from "$lib/components/ClicksCounter.svelte";


    let count=$state(5)
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<<<<<<< HEAD
<ClicksCounter bind:initialCount={count}/>

<p>count from parent is {count}</p>

<CanvasSquare/>
=======
<ClicksCounter initialCount={count}/>

>>>>>>> e88b783fd4a368a256a923453850371ab1148ccc

<style>
    h1 {
        color: deepskyblue;
    }
</style> 



