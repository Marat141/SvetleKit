<script>

</script>

<header>
    <nav>
        <a href="/">Home page</a>
        <a href="/">About</a>
        <a href="/">Svelte</a>   
    </nav>

</header>

<style>
    header{
        width: 100%;
        height: 100px;
        padding: 36px;
        box-sizing: border-box;
        background-color: rgba(61, 61, 62, 0.607);
        
    }

    nav{
        width: 100%;
        height: 100%;
        display: flex;
        gap: 36px;
        justify-content: flex-end;
        align-items: center; 
    }
    a{
            color: white;
            font-weight: 100%;
            text-decoration: none;
            transition: ease .3s;


    }
    a:hover{
        color: red;
    }


</style>