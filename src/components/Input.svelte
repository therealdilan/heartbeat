<script>

    export let placeholder

</script>

<input 
    on:click={() => message+= 'hello!'}
    class="bg-slate-300 px-4 font-medium py-2 text-slate-900 rounded transition-all outline-orange-400"
    placeholder={placeholder}
    />