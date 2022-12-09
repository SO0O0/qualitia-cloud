<template>
  <header>
    <div class="logo">
      <img alt="Vue logo" src="../assets/img/logo_qc.svg" />
    </div>
    <ul class="global_nav">
      <li>
        <a hreh="#">特徴</a>
      </li>
      <li>
        <a hreh="#">サービス紹介</a>
      </li>
      <li>
        <a hreh="#">プランと料金</a>
      </li>
      <li>
        <a hreh="#">ニュース</a>
      </li>
      <li>
        <a hreh="#">企業情報</a>
      </li>
    </ul>
    <a class="trial" href="#">無料トライアル</a>
    <a class="inquiry">お問い合わせ</a>
  </header>
</template>

<style lang="scss" scoped>
.logo {
  margin: auto 0;
}
.global_nav {
  display: flex;
  list-style: none;
  padding: 0 auto;
  margin-left: 350px;
  li {
    margin: auto 10px;
  }
}

.trial {
  width: 140px;
  font-weight: bold;
  width: 140px;
  text-align: center;
  color: #c6a96b;
  border: 1px solid #c6a96b;
  opacity: 1;
  padding: 15px;
  margin-left: 50px;
}

.inquiry {
  text-align: center;
  color: #fff;
  width: 140px;
  background-color: #c6a96b;
  opacity: 1;
  padding: 15px;
  margin-left: 10px;
}
</style>
