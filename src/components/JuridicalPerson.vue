<template>
  <section>
    <h1 class="fw-bold pb-3">
      Документација со барање за лизинг: ПРАВНИ ЛИЦА
    </h1>
    <p class="fs-5">
      Со пополнето барање за одобрување на лизинг, профактура на добавувачот и прифатена лизинг
      понуда потребно е да се приложат и:
    </p>
    <ul v-for="doc in documents" class="mb-0">
      <li class="fs-5" v-html="doc.text"></li>
    </ul>
    <br/>
    <p class="fs-5">
      Документација треба да биде заверена со потпис и печат на овластеното лице!
    </p>
    <p class="fs-5">
      <strong>AUTOWELT</strong> го задржува правото да побара дополнителна документација за разгледување на барањата за
      одобрување на лизинг.
    </p>
    <hr/>
    <i class="disclaimer-color">
      * НАПОМЕНА: ДОКОЛКУ ПОДАТОЦИТЕ КОИ ГИ ОСТАВАТЕ ПРИ ПРЕД-ОДОБРУВАЊЕТО НЕ СЕ ТОЧНИ И ПРЕЦИЗНИ МОЖНО Е АПЛИКАЦИЈАТА
      ЗА ЛИЗИНГ ДА ВИ БИДЕ ОДБИЕНА ИЛИ ПРОЛОНГИРАНА ОД СТРАНА НА БАНКАТА И ПРИТОА ГО ГУБИТЕ ОСТАВЕНИОТ КАПАР.
    </i>
  </section>
</template>

<script>
export default {
  name: "JuridicalPerson",
  data() {
    return {
      documents: [
        {
          text: `Барање за одобрување на лизинг <a href="https://s-leasing.mk/content/%D0%91%D0%B0%D1%80%D0%B0%D1%9A%D0%B5%20%D0%B7%D0%B0%20%D0%BE%D0%B4%D0%BE%D0%B1%D1%80%D1%83%D0%B2%D0%B0%D1%9A%D0%B5%20%D0%BD%D0%B0%20%D0%BB%D0%B8%D0%B7%D0%B8%D0%BD%D0%B3_Pravni%20Lica-11.01.2022.pdf" target="_blank">
                    <strong>(превземи барање)</strong></a>`
        },
        {
          text: `Копија од тековна состојба, не постара од 6 недели`
        },
        {
          text: `Завршна сметка (биланс на состојба и биланс на успех за последните две фискални години)`
        },
        {
          text: `Аналитички заклучни листови кон завршните сметки за последните две години`
        },
        {
          text: `Аналитички заклучен лист за тековната година со последен датум на книжење`
        },
        {
          text: `Согласност за извадок од Македонско Кредитно Биро <a href="https://s-leasing.mk/content/%D0%A1%D0%BE%D0%B3%D0%BB%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%20%D0%B7%D0%B0%20%D0%B8%D0%B7%D0%B2%D0%B0%D0%B4%D0%BE%D0%BA%20%D0%BE%D0%B4%20%D0%9C%D0%B0%D0%BA%D0%B5%D0%B4%D0%BE%D0%BD%D1%81%D0%BA%D0%BE%20%D0%9A%D1%80%D0%B5%D0%B4%D0%B8%D1%82%D0%BD%D0%BE%20%D0%91%D0%B8%D1%80%D0%BE.pdf" target="_blank">
                    <strong>(превземи согласност)</strong></a>`
        },
        {
          text: `Изјава за вистински сопственик  <a href="https://s-leasing.mk/content/Izjava-za-vistinski-sopstvenik.pdf" target="_blank">
                    <strong>(превземи согласност)</strong></a>`
        }
      ]
    }
  }
}
</script>

<style scoped>
.disclaimer-color {
  color: red;
}
</style>