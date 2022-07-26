<template>
    <footer class="footer-container" id="footer">
        <address>
            <a href="tel:+5404626000">(540)462-6000</a>
        </address>
        <div class="links">
        
                <a href="https://www.instagram.com/pureeatslex/?hl=en">
                    <img src="../assets/instagram.png">
                    <p class="link">instagram</p>
                </a>


                <a href="https://www.facebook.com/PureEatsYum/">
                    <img src="../assets/facebook.png">
                    <p class="link">facebook</p>
                </a>

                <a href="https://www.tripadvisor.com/Restaurant_Review-g57896-d2334961-Reviews-Pure_Eats-Lexington_Virginia.html">
                    <img src="../assets/tripadvisor.png">
                    <p class="link">tripadvisor</p>
                </a>

                <a href="https://www.yelp.com/biz/pure-eats-lexington-2">
                    <img src="../assets/yelp.png">
                    <p class="link">yelp</p>
                </a>

        </div>
        <p class="copywrite">©PURE EATS INC.</p>
    </footer>
</template>

<style scoped>

.footer-container {
    background-color: rgb(80, 80, 110);
    height: 400px;
    font-size: 1.5rem;
}

address {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    height: 200px;
    font-size: 2rem
}

a {
    display: flex;
    align-items: center;
    text-decoration: none;
    color: black;
}

a:hover {
    color: wheat;
    text-shadow: 2px 2px black;
}

h5 {
    padding-right: 20px;
    font-weight: bold;
}


.links {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

img {
    width: 30px;
    margin-right: 10px;
}

.copywrite {
    text-align: center;
    font-size: 1rem;
    color: rgba(0, 0, 0, 0.8);
    margin-top: 50px;
}

@media screen and (max-width: 600px) {

    .footer-container {
        height: 250px;
        font-size: 0.8rem;
    }

    address {
        height: 100px;
        font-size: 1.5rem;
    }



}

@media screen and (max-width: 500px) {
    .footer-container {
        padding-bottom: 100px;
    }
}

@media screen and (max-width: 400px) {

    .link {
        display: none;
    }

}

</style>