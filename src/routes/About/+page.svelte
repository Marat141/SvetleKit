<script>

</script>


<section class="hero">
    <img src="https://www.souepl.cz/wp-content/uploads/2016/10/logo_stredni-1.jpg" alt="">
    <h1>Střední odborné učiliště, elektrotechnické Plzeň</h1>
    <p>Pojďte stavět svaší budoucnost u nás na škole, kde propojujeme praxi a vzdělání</p>
    <div class="hero-buttons">
        <a href="/about">Login</a>
        <a href="/" id="ghost">About</a>
    </div>
</section>

<style>
    .hero{
        width: 100%;
        min-height: calc(100vh - 100px);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;

    }

    .hero img{
        width: 250px;
    }

    .hero-buttons{
        display: flex;
        gap: 36px;

    }

    .hero-buttons a{
        color: white;
        background-color: rgb(36, 118, 29);
        text-decoration: none;
        width: 150px;
        height: 50px;

        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
        font-weight: 500;
        font-family: Arial, Helvetica, sans-serif;
        transition: ease 0.5s;
    }


    #ghost {
        color: black;
        background: none;
        border: 1px solid black;
        transition: ease 0.3s;
    }

    #ghost:hover{
        color: white;
        background: red; 
        border: 1px solid rgb(0, 0, 0); 
    }

    .hero-buttons a:hover{
        color: rgb(0, 0, 0);
        background: red;
    }
</style>