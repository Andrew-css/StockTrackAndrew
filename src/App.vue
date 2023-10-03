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
            <h4>Por favor, digite su correo para el proceso de recuperación de contraseña</h4>
          </div>
            <div>
              <h3>Correo electrónico</h3>
              <input type="text">
            </div>
            <div>
              <button>Recuperar contraseña</button>
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
.body{
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.half{
  width: 100%;
  height: 100%;

}
.barras{
  width: 100%;
  background-color: #EEEEEE;
  height: 60px;
}
.image{
  margin-left: 20px;
  margin-top: 20px;
  display: flex;
}

img{
  border-radius: 100%;
  width: 250px;
  height: 250px;
}

.text{
  font-family: Arial, Helvetica, sans-serif;
  text-decoration: none;
  font-size: 30px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.text1{
  width: 50%;
}
</style>
