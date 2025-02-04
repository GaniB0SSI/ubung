<script>
    let {children} = $props();
    import "../style.css"
</script>


<header> 
    Welcome to my project
</header>
<div class="maini">
<main> 
    {@render children()}
</main>
</div>
<footer>
    This is the footer, all rights preserved.
</footer>

<style>
    header {
        background-color: #007bff;
        color: white;
        text-align: center;
        padding: 20px;
        font-size: 24px;
        font-weight: bold;
    }
    .maini{
        display: flex;
        justify-content: center;
        padding: 10px solid black;
    }
    main {
        padding: 20px;
        min-height: 60vh;
        font-size: 18px;
        color: #333;
    }

    footer {
        background-color: #222;
        color: white;
        text-align: center;
        padding: 15px;
        font-size: 14px;
    }
</style>