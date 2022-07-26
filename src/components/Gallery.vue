<template>
    <div class="gallery-container">
        <h3><em>GALLERY</em></h3>
        <div class="gallery">
            <img class="arrow" src="../assets/left-arrow.png" @click="decrement">
            <img 
                class="gallery-image animated" 
                :src="imageUrl"
                :key="imageUrl"
            >
            <img class="arrow" src="../assets/right-arrow.png" @click="increment">
        </div>
    </div>
</template>

<script>
    

    export default {
        name: 'Gallery',
        methods: {
            increment() {
                if (this.id === this.maxImages) {
                    this.id = 1
                    this.imageUrl = require(`../assets/gallery-image-${this.id}.jpeg`)
                    return
                }
                this.id ++
                this.imageUrl = require(`../assets/gallery-image-${this.id}.jpeg`)

            },
            decrement() {
                if (this.id === 1) {
                    this.id = this.maxImages
                    this.imageUrl = require(`../assets/gallery-image-${this.id}.jpeg`)
                    return

                }
                this.id --
                this.imageUrl = require(`../assets/gallery-image-${this.id}.jpeg`)

            }
        },
        data() {
            return {
                id: 1,
                maxImages: 8,
                imageUrl: require('../assets/gallery-image-1.jpeg')
            }
        },
        created() {
            setInterval(() => {
                this.increment()
            }, 4000)
        }
    }
</script>

<style scoped>

.gallery-container {
    background-color: white;
    margin: 0;
    border-top: 2px solid rgb(250,90,90);
}

h3 {
    font-size: 2rem;
    color: black;
    text-shadow: 2px 2px rgb(250,90,90);
    padding: 25px;
    margin: 0;
    position: relative;
    top: 30px;
    left: 40px;
    max-width: 50%;
}

.gallery {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
    bottom: 50px;
}

.arrow {
    width: 30px;
    padding: 8px;
    margin: 30px;
    border: transparent;
    border-radius: 15px;
    background-color: rgba(105, 90, 205, 0.4);

}

.gallery-image {
    height: 500px;
    margin: 0 5%;
    border: 3px solid slateblue;
    border-radius: 5px;
}

.animated {
    animation: switchImage;
    animation-duration: 0.8s;
}

@media screen and (max-width: 1100px) {
    .gallery-image {
        height: 400px;
    }

    h3 {
        left: 20px;
    }
}

@media screen and (max-width: 960px) {
    .gallery-container {
        display: none;
    }
    
}

@keyframes switchImage {
    from {opacity: 0;}
    to {opacity: 1;}
}

</style>