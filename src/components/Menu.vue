<template>
    <div class="menu-container" id="menu">
        <div class="title">
            <div class="title-headers">
                <h3><em>Menu</em></h3>
                <a href="#buttons" id="order-below">Order Online Below</a>
            </div>
            <div class="header-links">
                <a href="#breakfast-title">breakfast</a>
                <a href="#lunch/dinner-title">lunch/dinner</a>
                <a href="#sides-title">sides</a>
            </div>
        </div>
        <div class="menu">  

            <div>
            <h4 class="header" id="breakfast-title">BREAKFAST</h4>
            <dl class="breakfast">
                <dt>Doughnuts</dt>
                <dd>Flavors change daily, but we have classic cinnamon-sugar every day.</dd>

                <dt>Breakfast Sandwiches</dt>
                <dd>Your choice of local sausage, farm-fresh eggs, cheese, and thick-cut smoked bacon on a toasted roll.</dd>

                <dt>Bagels</dt>
                <dd>Everything, Plain, Asiago, Cinnamon Raisin, and Whole Wheat</dd>

                <dt>Bagel Sandwiches</dt>
                <dd>Your choice of local sausage, farm-fresh eggs, cheese, and thick-cut smoked bacon on a bagel of your choice.</dd>

                <dt>Hash Browns</dt>
                <dd>A very tasty addition to your breakfast.</dd>

                <dt>The General</dt>
                <dd>Two farm-fresh eggs, local sausage or thick cut bacon and toast.</dd>

                <dt>Rockbridge Roll-Up</dt>
                <dd>Burrito stuffed with 2 farm-fresh eggs, shredded cheese, salsa an hashbrowns. Add bacon, sausage, avocado</dd>

                <dt>The Keydet</dt>
                <dd>Burrito stuffed with 2 farm-fresh eggs, shredded cheese, salsa an hashbrowns. Add bacon, sausage, avocado</dd>
            </dl>
            </div>
            <div>

            <h4 class="header" id="lunch/dinner-title">LUNCH / DINNER</h4>
            <dl class="lunch-dinner">
                <dt>Hamburger</dt>
                <dd>Featuring fresh, all-natural local beef from Buffalo Creek Beef, our burgers are the best.</dd>

                <dt>NoBull Veggie Burger</dt>
                <dd>We carry the NoBull veggie burger, a flavorful, organic alternative to meat.</dd>

                <dt>Locally Sourced Organic Chicken Sandwich</dt>
                <dd>Grilled or breaded, you cannot go wrong with this chicken sandwich.</dd>

                <dt>Hot Dog</dt>
                <dd>This all beef hot dog is made from the same local beef as our burgers, and is just as delicious.</dd>

                <dt>Double Burger</dt>
                <dd>Just like a regular burger, but double.</dd>

                <dt>Special Burger</dt>
                <dd>Changes weekly, examples are California Burger (avocado, jack cheese, lettuce, tomato, onion), Mushroom-Bacon-Swiss, and the Carprese Burger (tomato, basil, mozzarella).</dd>

                <dt>Wraps</dt>
                <dd>Just like a chicken sandwich, but in a wrap.</dd>

                <dt>Salad</dt>
                <dd>Just like a wrap, but on a plate.</dd>

                <dt>Burgers Toppings:</dt>
                <dd>
                    Lettuce, Tomato, Pickles, Onions (grilled or fresh) <br>
                    Cheeses: Cheddar, American, Provolone, Swiss, Pepper Jack
                </dd>

                <dt>Extras:</dt>
                <dd>Thick cut Bacon, Farm Fresh Fried Egg, Jalapenos, Avocado, Sauteed Mushrooms</dd>

                <dt>Bread Options:</dt>
                <dd>Homemade Potato Roll, Lettuce Wrap, Gluten Free Bun, Tortilla Wrap</dd>
            </dl>
            </div>
            <div>

            <h4 class="header" id="sides-title">SIDES</h4>
            <dl class="sides">
                <dt>French Fries</dt>
                <dd>(think early 90's) crispier, crunchier and a hint of salt.</dd>

                <dt>Beef Tallow Fries</dt>
                <dd>Our hand-cut fries cooked in rendered beef fat</dd>

                <dt>Onion Rings</dt>
                <dd>Like fries, but with onions.</dd>

                <dt>Sweet Potato Fries</dt>
                <dd>Like regular fries, but sweet (you get the idea).</dd>

                <dt>Route 11 Chips</dt>
                <dd>Lightly salted, barbecue, and jalapeño potato chips.</dd>

                <dt>Soup or Stew</dt>
                <dd>Changes weekly, but we often have homemade Buffalo Creek Beef Chili and Brunswick Stew.</dd>

                <dt>Fried Pickles</dt>
                <dd>Our pickle chips (not spears!) are crispy and delicious.</dd>

                <dt>Fried Mushrooms</dt>
                <dd>Whole mushrooms breaded and deep fried</dd>

                <dt>Milkshakes</dt>
                <dd>We use only all-natural Homestead Creamery ice cream in our rich, velvety shakes.</dd>
            </dl>
            </div>
        </div>
    </div>
</template>


<style scoped>
    .title-headers {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .title {
        display: flex;
        flex-direction: column;
        padding: 10px 15% 10px 15%;
        background-color: aliceblue;
        border-top: 1px solid rgb(250,90,90);
    }

    .header-links {
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 3%;
    }

    .header {
        color: skyblue;
        text-shadow: 2px 2px blueviolet;
        display: flex;
        justify-content: space-around;
        align-items: center;
        font-size: 2rem;
        font-weight: 50;
    }




    dl {
        padding: 0 5%;
        font-family: Arial, sans-serif;
        max-width: 100%;
        letter-spacing: 1px;
        line-height: 120%;
        text-shadow: 2px 1px black;
    }

    dt {
        text-align: left;
        margin-bottom: 5px;
        font-weight: bolder;
        font-size: 1.1rem;
    }

    dd {
        text-align: left;
        margin: 0 0 15px 0;
        font-weight: lighter;
    }


    h3 {
        color: black;
        text-shadow: 2px 2px rgb(250,90,90);
        font-size: 2rem;
    }

    a {
        font-size: 1.4rem;
        color: black
    }

    a:hover {
        color: rgb(250,90,90);

    }

    .menu {
        background-image: url('../assets/menu-background.jpeg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        color: white;
        display: flex;
        justify-content: space-around;
        padding: 5% 10% 3% 10%;
    }

    @media screen and (max-width: 750px) {
        .menu {
            background-image: none;
            background-color: rgb(80, 80, 110);
            flex-direction: column;
            padding: 5% 5% 2% 5%;
        }

        .title {
            font-size: 0.7rem;
            padding: 10px 5%;
        }

        .header {
            margin: 10% 0 5% 0;
        }

        
    }

    @media screen and (max-width: 500px) {
        #order-below {
            display: none;
        }

          .title-headers {
            height: 80px;
            flex-direction: column;
            padding: 0 5% 15px 5%;
        }

        a {
            font-size: 1rem;
        }
    }

    @media not screen and (max-width: 500px) {
        .header-links {
            display: none;
        }
    }

</style>