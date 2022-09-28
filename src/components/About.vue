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
        margin: 0 10%;
    }

    img {
        max-height: 200px;
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