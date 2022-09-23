<template>
  <div class="calculadora">
   <div class="display">0</div>
   <div class="botao">%</div>
   <div class="botao">√</div>
   <div class="botao">C</div>
   <div class="botao">÷</div>
   <div class="botaoNum">7</div>
   <div class="botaoNum">8</div>
   <div class="botaoNum">9</div>
   <div class="botao">x</div>
   <div class="botaoNum">4</div>
   <div class="botaoNum">5</div>
   <div class="botaoNum">6</div>
   <div class="botao">-</div>
   <div class="botaoNum">1</div>
   <div class="botaoNum">2</div>
   <div class="botaoNum">3</div>
   <div class="botao">+</div>
   <div class="botao">+/-</div>
   <div class="botaoNum">0</div>
   <div class="botao">,</div>
   <div class="botaoResul">=</div>
  </div>
</template>

<script>
export default {

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.calculadora{
  font-size: 15px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}

.display{
  grid-column: 1 / 5;
  background-color: #333;
  color: white;
}

.botao{
  background-color: #afafaf;
  border: 1px solid rgb(119, 119, 119);
}

.botaoNum {
  border: 1px solid rgb(119, 119, 119);
}

.botaoResul{
  background-color: orangered;
  border: 1px solid rgb(119, 119, 119);
  color: white;
}
</style>
