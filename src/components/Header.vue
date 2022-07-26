<template>
    <div class="header-container">
        <header class="top-bar">
            <a href="#map" class="location"><strong>LOCATION</strong></a>
            <a href="#menu" class="menu"><strong>MENU</strong><br><p><em>order online!</em></p></a>
            <img src="../assets/pure-eats-logo.gif" alt="logo loading. . ." class="logo">
            <a href="#about" class="about"><strong>ABOUT</strong></a>
            <a href="#footer" class="footer"><strong>CONTACT US</strong></a>
        </header>
        <div class="header-image"></div>
        
        
    </div>
</template>

<script>
    export default {
        name: 'Header',
    }
</script>

<style scoped> 
    .header-container {
        /* height: 1000px; */
        margin: 0;
    }

    .top-bar {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        background-color: white;
        height: 250px;
        padding: 0 3%;
    }

    .logo {
        width: 180px
    }

    .header-image {
        background-image: url('../assets/header-image.png');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: bottom;
        height: 750px;
    }

    a {
        color: rgb(170,40,40);
        text-decoration: none;
        text-align: center;
        font-size: 2rem;
    }

    a:hover {
        color:rgb(100, 90, 170)
    }

    .menu {
        padding-top: 18px
    }

    p {
        font-size: 1rem;
        margin: 0;
        text-align: center;
    }

   @media screen and (max-width: 960px) {
    a {
        font-size: 1.8rem;
    }

    .top-bar {
        flex-direction: row-reverse;
        padding: 0 15% 0 3%;
        justify-content: space-between;
        height: 150px
    }

    .footer {
        display: none;
    }

     .about {
        display: none;
    }

    .logo {
        width: 100px;
    }

    .header-image {
        height: 500px;
    }

    
   }

   @media screen and (max-width: 400px) {
        a {
            font-size: 1.2rem;
        }

        p {
            display: none;
        }

        .menu {
            padding-top: 0;
        }

         .header-image {
        height: 200px;
        background-size: cover;
        }
   }

</style>