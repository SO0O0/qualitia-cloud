<template>
  <section id="main_vidual">
    <div class="container">
      <img class="logo" alt="logo" src="../assets/img/logo_qc_white.svg" />
      <div class="catchphrase">
        <p class="phrase">企業リスクと真面目に向き合う</p>
        <p class="about">
          純国産 ビジネス
          <br />プラットフォーム
        </p>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
// svgを白く塗りつぶす
.logo {
  fill: #fff;
  width: 500px;
}

.catchphrase {
  font-family: "Noto Serif JP", serif;
  font-weight: 500;
  margin-top: 80px;
  font-size: 25px;
  color: #fff;

  .phrase {
    font-size: 28px;
    font-weight: thin;
  }

  .about {
    margin-top: 30px;
    font-size: 40px;
    line-height: 1.5;
    font-weight: medium;
  }
}
</style>
