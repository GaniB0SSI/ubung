<script>
    // Destructuring children from props (likely passed from a parent component)
    let { children } = $props();

    // Importing an external stylesheet for styling
    import "../style.css";
</script>

<header> 
    <!-- This is the main header of the page -->
    <!-- It displays a welcome message to the users -->
    Welcome to my project
</header>

<div class="maini">
    <main> 
        <!-- Rendering the children passed to this component *-->
        {@render children()}
    </main>
</div>

<footer>
    This is the footer, all rights preserved.
</footer>

<style>
    /* Styling for the header */
    header {
        background-color: #007bff;
        color: white; 
        text-align: center;
        padding: 20px;
        font-size: 24px; 
        font-weight: bold; 
    }

    /* Container for the main content */
    .maini {
        display: flex;
        justify-content: center; 
        padding: 10px solid black; 
    }

    /* Styling for the main section */
    main {
        padding: 20px; 
        min-height: 60vh; 
        font-size: 18px; 
        color: #333; 
    }

    /* Styling for the footer */
    footer {
        background-color: #222; 
        color: white; 
        text-align: center; 
        padding: 15px; 
        font-size: 14px; 
    }
</style>
