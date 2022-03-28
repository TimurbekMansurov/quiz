<template>
  <div class="main">
    <div class="header">
        <h1> Викторина по IT</h1>
    </div>
    <div class="quizing">
        <h4 class="h4">Начать викторину</h4>
        <p class="p">Вам зададут 10 рандомно выбранных вопросов.</p> 
    </div>
     <div class="themes">
        <h4 class="h4">Викторина на определенную тему</h4>
        <p class="p">Выберите тему викторины, после чего все вопросы будут касательно выбранной темы.</p>
    </div>
    <div class="history">
        <h4 class="h4">История</h4>
        <p class="p">Узнайте результат пройденных ранее викторин, дату прохождения и балл.</p>
    </div>
    <div class="basement">
        <p class="p">Наш номер телефона: +7 968 *** ** **</p>
        <p class="p">Наша почта: victorina@gmail.com</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.h1 {
    color: rgb(80, 112, 21);
    text-align: center;
    font-size: 40px;
}
.h4 {
    color: rgb(80, 112, 21);
    text-align: center;
    font-size: 32px;
}
.p {
    color: rgb(80, 112, 21);
    text-align: center;
    font-size: 24px;
}
.header {
    color: rgb(80, 112, 21);
    text-align: center;
}
.basement {
    color: rgb(80, 112, 21);
    border-top: 6px solid rgb(0, 0, 0);
    text-align: center;
}
.quizing {
    color: rgb(80, 112, 21);
    border: 6px solid rgb(0, 0, 0);
    text-align: center;
    margin: 42px;
    background: rgb(141, 195, 90);
}
.themes {
    color: rgb(80, 112, 21);
    border: 6px solid rgb(0, 0, 0);
    text-align: center;
    margin: 42px;
    background: rgb(141, 195, 90);
}
.history {
    color: rgb(80, 112, 21);
    border: 6px solid rgb(0, 0, 0);
    text-align: center;
    margin: 42px;
    background: rgb(141, 195, 90);
}
.main {
     background: rgb(159, 180, 67);
}
</style>