// Configurações 

<template>
  <container class="cont" style="background-color:red">
    <headers/>
    <div class="principal">
      <div class="base">
        <h1>Configurações</h1>
        <div class="cards">
            <section class="card_one">
                <!-- <img src="" alt="Avatar"> -->
                <h1>Cadastrar Usuario</h1>
            </section>
         
            <section class="card_two">
                <!--  <img src="/consulta.png" alt="consulta">    -->
                <h1>Consultar Usuario</h1>             
            </section>
            
        </div>
      </div>
    </div>  
    <footers/>
  </container>
</template>

<script>

export default {
  name: 'home',
}

</script>

<style lang="scss" scoped>
@import "@/layouts/variaveis.scss"; 

.cont{
  height: $conte;
}

.principal{
  background-color: #E5E5E5;
  position: absolute;
  top: $alturaHeader;
  bottom: $alturaFooter;
  background-color: #E5E5E5;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.base{
  background-color: #fff;
  width: 55%;
  height: auto;
  padding: 3%;
  align-items: center;
  border-radius: 3px;
  margin: 100px;
  justify-content: space-between;
}

h1{
  font-weight: bold;
  text-align: center;
}

.cards {
  width: 80%;
  height: 55vh;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  background-color: white;
  margin-left:10%;
  justify-content: space-between;
}

.card_one {
   background-color: rgb(235, 235, 235);
   width: 40%;
   height: 35%;
   border-radius: 5px;
   border-style: solid;
}

.card_two {
   background-color: rgb(235, 235, 235);
   width: 40%;
   height: 35%;
   border-radius: 5px;
   border-style: solid;
}

</style>