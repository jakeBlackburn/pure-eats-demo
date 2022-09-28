<template>
    <div class="buttons" id="buttons">
      <span class="menu" data-glf-cuid="d60d3a38-ac6b-40a6-8f8f-9d5c994ac103" data-glf-ruid="5827ca57-3ae7-45c3-bc94-20224a22e38c" >Order Online</span> 
      <span class="reservation" data-glf-cuid="d60d3a38-ac6b-40a6-8f8f-9d5c994ac103" data-glf-ruid="5827ca57-3ae7-45c3-bc94-20224a22e38c" data-glf-reservation="true" > Table Reservation</span>
    </div>
</template>

<style scoped>
.buttons {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: rgba(255, 255, 255, 0.8);
  height: 150px;
  border-top: 1px solid black;
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