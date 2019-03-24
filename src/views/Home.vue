<template>
  <div >
    <h3>Обо мне</h3>
    <p>Я, Маркин Сергей Андреевич 27.08.1999, студент университета "Иннополис", 2 курс (на 2018-2019 год).
      Програмированием занимаюсь около 5 лет(начал со спортивного программировния).
      Сейчас больше года занимаюсь фронтенд разработкой.
      В данный момент работаю в ООО "Намисофт", на должности "программист клиентской системы".
    </p>
    <h3>Профессиональные навыки</h3>
    <div id="mylist">
    <ol>
      <li>HTML</li>
      <li>Js</li>
      <li>CSS3</li>
      <li>VueJs</li>
      <li>Webpack</li>
      <li>Git</li>
    </ol>
    </div>
    <div>
      <h3>Опыт работы</h3>
      <table class="mytable">
        <tr>
          <th class="left_column">Даты</th>
          <th class="right_column">Место работы</th>
        </tr>
        <tr>
          <td class="left_column">08.08.2018-сегодня</td>
          <td class="right_column">ООО "Намисофт", на должности "программист клиентской системы"</td>
        </tr>
        <tr>
          <td class="left_column">01.01.2018-08.08.2018</td>
          <td class="right_column">Фриланс, доработка чужих сайтов, замена контента, лендинги,<a href="http://liverart.ru/">магазин-корма</a></td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',
  components: {
  }
}
</script>
<style scoped>
  #mylist { width:320px; }
  #mylist ol {
    font-size:24px;  }
  p{
    font-size:20px;
  }
  .mytable{
    width: 100%;
    border: 2px solid #e1e1e1;
  }
  .left_column{
    width: 10%;
  }

  .right_column{
    width: 90%;
  }
</style>
