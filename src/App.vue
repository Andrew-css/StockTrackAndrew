<template>
  <div class="body">
    <div class="barras">
    </div>

    <div class="half">
      <div class="image">
        <img src="./assets/Stocktrack.jpg" alt="">
      </div>
      <div class="text">
        <div class="text1">
          <p class="Message">Por favor, digite su correo para el proceso de recuperación de contraseña</p>
        </div>
        <div class="text2">
          <h3>Correo electrónico</h3>

        </div>
        <div class="text3">
          <input type="text" class="inputcorreo">
          <button class="buttonpassword">Recuperar contraseña</button>
        </div>
      </div>
    </div>

    <div class="barras">
    </div>

  </div>
</template>




<script setup>

</script>




<style scoped>
.body {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.half {
  width: 100%;
  height: 100%;

}

.barras {
  width: 100%;
  background-color: #EEEEEE;
  height: 60px;
}

.image {
  margin-left: 20px;
  margin-top: 20px;
  display: flex;
}

img {
  border-radius: 100%;
  width: 200px;
  height: 200px;
}

.text {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 30px;
  display: flex;
  flex-direction: column;
  align-items: center;

}

.text1 {
  width: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.text2 {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.Message {
  text-align: center;

}

.text3 {
  display: flex;
  flex-direction: column;
  gap: 60px;
  align-items: center;
}

.inputcorreo {
  width: 408px;
  height: 45px;
  flex-shrink: 0;
  fill: var(--Final, #EEE);
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  background-color: #eeeeee;
  border: none;
  border-radius: 10px;
  font-size: 1em;
}

.buttonpassword {
  background-color: #00adb5;
  color: white;
  font-weight: bolder;
  font-size: 25px;
  border-radius: 25px;
  cursor: pointer;
  width: 500px;
  height: 40px;
}

@media screen and (min-width: 390px) and (max-width: 520px){
  .inputcorreo{
    width: 288px;
  }
  .buttonpassword{
    width: 390px;
  }
}

@media screen and (min-width: 0px) and (max-width: 389px){

  .inputcorreo{
    width: 230px;
  }
  .buttonpassword{
    width: 300px;
  }
}


</style>
