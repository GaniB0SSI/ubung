<script>
        // Declaring a reactive state variable "message" with an initial value of "hello"
    let message = $state("hello");
</script>


<!-- Displaying the message inside an <h1> tag -->
<h1>{message}</h1>
<!-- Input field bound to "message" so changes update automatically -->
<input bind:value={message} />