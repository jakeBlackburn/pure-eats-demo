<template>
  <div class="top-container">
    <Header />
    <Menu />
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import Menu from './components/Menu.vue'


  export default {
    name: 'Top',
    components: {
      Header,
      Menu
    }
  }
</script>

<style>

body {
  background-color: rgb(170,40,40);
  margin: 0;
  font-family: 'Bebas Neue';
}

.buttons {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: rgba(255, 255, 255, 0.8);
  height: 150px;
  border-top: 2px solid slateblue;
  font-size: 3rem;
  text-decoration: underline;
  text-shadow: 1px 1px rgb(250,90,90);
}

span:hover {
  color: rgb(250,90,90);
  text-shadow: none;
  cursor: pointer;
}

@media screen and (max-width: 720px) {
    .buttons {
      font-size: 2rem;
    }
}

@media screen and (max-width: 500px) {
    .buttons {
      font-size: 1.5rem;
      position: fixed;
      width: 100%;
      height: 100px;
      bottom: 0;
    }
}


</style>
