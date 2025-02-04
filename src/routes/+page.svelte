<script>
    let message = $state("hello");
</script>



<h1>{message}</h1>
<input bind:value={message} />