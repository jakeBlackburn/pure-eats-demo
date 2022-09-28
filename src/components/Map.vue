<template>
    <div class="location-container">
        <h4 id="map">LOCATION</h4>
        <p class="location-text"><strong>Downtown Lexington VA, </strong><br> 107 N Main Street</p>
        <a href="https://www.google.com/maps/place/Pure+Eats/@37.7864637,-79.4416576,18.51z/data=!4m5!3m4!1s0x884ccbba4d3822ed:0xbc231d4c6d94225b!8m2!3d37.7864448!4d-79.4403948">view on Google Maps</a>
    </div>
</template>

<style scoped>
 .location-container {
        text-align: center;
        background-color: aliceblue;
        height: 250px;
    }

    h4 {
        text-align: center;
        padding-top: 20px;
        margin-top: 0;
        font-size: 2.5rem;
        margin-bottom: 20px;
    }

    .location-text {
        padding-bottom: 50px;
    }

    a {
        padding: 10px;
        border-radius: 5px;
        margin-top: 20px;
        text-decoration: none;
        background-color: rgb(135, 155, 235);
        color: white;
        border: 1px solid black;
        text-shadow: 1px 1px black;
        font-size: 1.3rem;
    }

    a:hover {
        color: rgb(250,90,90);
        background-color: whitesmoke;
    }

     @media screen and (max-width: 720px) {
        p {
            margin: 0 5%;
            font-size: 0.8rem;
        }

        h4 {
            font-size: 2rem;
        }
    }

</style>