<template>
  <section>
    <h1 class="fw-bold pb-3">
      Документација со барање за лизинг: ФИЗИЧКИ ЛИЦА
    </h1>
    <p class="fs-5">
      Со пополнето барање за одобрување на лизинг, <strong>профактура на добавувачот</strong> и <strong>прифатена лизинг
      понуда</strong>, потребно е да се приложат и:
    </p>
    <ul v-for="doc in documents" class="mb-0">
      <li class="fs-5" v-html="doc.text"></li>
    </ul>
    <br>
    <strong>
      <p class="fs-5">
        Документација треба да биде заверена со потпис и печат на овластеното лице!
      </p>
    </strong>
    <p class="fs-5">
      <strong>AUTOWELT</strong> го задржува правото да побара дополнителна документација за разгледување на барањата за
      одобрување на лизинг.
    </p>
  </section>
</template>

<script>
export default {
  name: "PhysicalPerson",
  data() {
    return {
      documents: [
        {
          text: `ПРОФАКТУРА`
        },
        {
          text: `БАРАЊЕ за одобрување на лизинг <a href="https://s-leasing.mk/content/%D0%91%D0%B0%D1%80%D0%B0%D1%9A%D0%B5%20%D0%B7%D0%B0%20%D0%BE%D0%B4%D0%BE%D0%B1%D1%80%D1%83%D0%B2%D0%B0%D1%9A%D0%B5%20%D0%BD%D0%B0%20%D0%BB%D0%B8%D0%B7%D0%B8%D0%BD%D0%B3-Fizicki%20Lica.pdf" target="_blank">
                    <strong>(превземи барање)</strong></a>`
        },
        {
          text: `Копија од ЛИЧНА КАРТА`
        },
        {
          text: `ПОТВРДА од работодавецот за редовен работен однос`
        },
        {
          text: `Административна забрана од плата од работодавецот <a href="https://s-leasing.mk/content/%D0%90%D0%B4%D0%BC%D0%B8%D0%BD%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D0%B0%20%D0%B7%D0%B0%D0%B1%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D0%B4%20%D0%BF%D0%BB%D0%B0%D1%82%D0%B0%20%D0%BE%D0%B4%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D0%B4%D0%B0%D0%B2%D0%B5%D1%86%D0%BE%D1%82%20%D0%B2%D0%BE%20%D0%BA%D0%BE%D1%80%D0%B8%D1%81%D1%82%20%D0%BD%D0%B0%20%D0%A8%D0%9F%D0%90%D0%A0%D0%9A%D0%90%D0%A1%D0%95%20%D0%9B%D0%98%D0%97%D0%98%D0%9D%D0%93%20%D0%94%D0%9E%D0%9E%20%D0%A1%D0%BA%D0%BE%D0%BF%D1%98%D0%B5.pdf" target="_blank">
                    <strong>(превземи барање)</strong></a>`
        },
        {
          text: `ИЗЈАВА за редовна отплата <a href="https://s-leasing.mk/content/%D0%98%D0%B7%D1%98%D0%B0%D0%B2%D0%B0%20%D0%B7%D0%B0%20%D1%80%D0%B5%D0%B4%D0%BE%D0%B2%D0%BD%D0%B0%20%D0%BE%D1%82%D0%BF%D0%BB%D0%B0%D1%82%D0%B0.pdf" target="_blank">
                    <strong>(превземи барање)</strong></a>`
        },
        {
          text: `Годишна даночна пријава (доколку барателот остварува дополнителни приходи)`
        },
        {
          text: `Декларации за прием за бруто плата за последните 3 месеци`
        },
        {
          text: `СОГЛАСНОСТ за извадок од Македонско Кредитно Биро <a href="https://s-leasing.mk/content/%D0%A1%D0%BE%D0%B3%D0%BB%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%20%D0%B7%D0%B0%20%D0%B8%D0%B7%D0%B2%D0%B0%D0%B4%D0%BE%D0%BA%20%D0%BE%D0%B4%20%D0%9C%D0%B0%D0%BA%D0%B5%D0%B4%D0%BE%D0%BD%D1%81%D0%BA%D0%BE%20%D0%9A%D1%80%D0%B5%D0%B4%D0%B8%D1%82%D0%BD%D0%BE%20%D0%91%D0%B8%D1%80%D0%BE.pdf" target="_blank">
                    <strong>(превземи согласност)</strong></a>`
        },
      ]
    }
  }
}
</script>

<style scoped>
</style>