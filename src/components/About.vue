<template>
    <div class="about-container" id="about">
        <h2 class="title">ABOUT PURE EATS</h2>
        <p><strong>Pure Eats</strong> is dedicated to providing the highest quality, locally sourced food in a fun, family-friendly atmosphere.</p>
        <p>Our approach is very simple. Our legendary burgers, for example, start with the best ground beef in the world, which happens to come from our Rockbridge County neighbors, the Potter family of <strong>Buffalo Creek Beef</strong> and <strong>Donald's Meats</strong>. We then cook it to order with great care, and serve it up in a setting that is comfortable and friendly. The result is maybe just a hamburger, but it's important to us that it be the best.</p>
        <p>We also feature fresh, house-made doughnuts every morning, locally roasted coffee, breakfast sandwiches, salads and wraps, rich <strong>Homestead Creamery</strong> milk shakes, and a selection of great local craft beer and cider.</p>
        <h6><em>Open 8AM to 8PM Monday-Sunday</em></h6>
        <div class="images">
            <img src="../assets/buffalo-creek-beef.jpeg" >
            <img src="../assets/donalds-meats.jpeg" >
            <img src="../assets/homestead-creamery.jpeg" >
        </div>
        <div class="location-container">
            <h4 id="map">LOCATION</h4>
            <p class="location-text"><strong>Downtown Lexington VA, </strong><br> 107 N Main Street</p>
            <a href="https://www.google.com/maps/place/Pure+Eats/@37.7864637,-79.4416576,18.51z/data=!4m5!3m4!1s0x884ccbba4d3822ed:0xbc231d4c6d94225b!8m2!3d37.7864448!4d-79.4403948">view on Google Maps</a>
        </div>
    </div>
</template>

<style scoped>
    .about-container {
        background-color: white;
    }

    .title {
        text-align: center;
        padding: 30px;
        font-size: 2.8rem;
        letter-spacing: 2px;
        margin: 0;
    }

    p {
        font-size: 1.2rem;
        font-family: Arial, sans-serif;
        margin: 0 20%;
        letter-spacing: 1px;
        padding: 10px 0;
        color:rgba(0, 0, 0, 0.901);
    }

    h6 {
        text-align: center;
        font-size: 2rem;
    }

    .images {
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: 0 10% 30px 10%;
    }

    img {
        max-height: 200px;
    }

    .location-container {
        text-align: center;
        background-color: aliceblue;
        height: 250px;
    }

    h4 {
        text-align: center;
        padding-top: 20px;
        margin-top: 10px;
        font-size: 2.5rem;
        margin-bottom: 20px;
    }

    .location-text {
        padding-bottom: 50px;
    }

    a {
        padding: 10px;
        border: 3px solid slateblue;
        border-radius: 5px;
        margin-top: 20px;
        text-decoration: none;
        background-color: rgb(135, 155, 235);
        color: white;
        text-shadow: 2px 2px black;
        font-size: 1.2rem;
    }

    @media screen and (max-width: 720px) {
        p {
            margin: 0 5%;
            font-size: 0.8rem;
        }

        .title {
            font-size: 2rem;
        }

        h4 {
            font-size: 2rem;
        }

        h6 {
            font-size: 1.5rem;
        }

        img {
            display: none;
        }
    }





</style>