<script>

    let message = ''

    export let text

</script>

<button on:click={() => message+= 'hello!'}
    class="bg-slate-700 p-4">
    {text}
</button>

{message}