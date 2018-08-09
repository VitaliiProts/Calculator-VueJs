<template>
  <div class="calculator">
    <div class="calculator-display">{{current || '0'}}</div>
    <div @click="clear" class="calculator-btn">C</div>
    <div @click="sign" class="calculator-btn">+/-</div>
    <div @click="percent" class="calculator-btn">%</div>
    <div @click="divide" class="calculator-btn operator">÷</div>
    <div @click="append('7')" class="calculator-btn">7</div>
    <div @click="append('8')" class="calculator-btn">8</div>
    <div @click="append('9')" class="calculator-btn">9</div>
    <div @click="times" class="calculator-btn calculator-operator">x</div>
    <div @click="append('4')" class="calculator-btn">4</div>
    <div @click="append('5')" class="calculator-btn">5</div>
    <div @click="append('6')" class="calculator-btn">6</div>
    <div @click="minus" class="calculator-btn calculator-operator">-</div>
    <div @click="append('1')" class="calculator-btn">1</div>
    <div @click="append('2')" class="calculator-btn">2</div>
    <div @click="append('3')" class="calculator-btn">3</div>
    <div @click="add" class="calculator-btn calculator-operator">+</div>
    <div @click="append('0')" class="calculator-btn calculator-zero">0</div>
    <div @click="dot" class="calculator-btn">.</div>
    <div @click="equal" class="calculator-btn calculator-operator">=</div>
  </div>
</template>

<script src='./index.js'></script>
<style lang="scss" src='./index.scss'></style>
