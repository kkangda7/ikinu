<template>
  <div>
    <Header></Header>
    <div class="setup">
    <div class="setup__body">
      <dl class="setup__body__list">
        <dt>各種設定</dt>
        <dd>
          <button class="btn btn--medium btn--flat_orange">プロフィール編集</button>
        </dd>
        <dd>
          <button class="btn btn--medium btn--flat_orange">メールアドレス編集</button>
        </dd>
        <dd>
          <button class="btn btn--medium btn--flat_orange">パスワード編集</button>
        </dd>
        <dd>
          <button class="btn btn--medium btn--flat_orange">お問い合わせ</button>
        </dd>
        <dd>
          <button class="btn btn--medium btn--flat_orange">利用契約</button>
        </dd>
        <dd>
          <button class="btn btn--medium btn--flat_orange">プライバシーポリシー</button>
        </dd>
      </dl>
    </div>
  </div>
  <Footer></Footer>
</div>

</template>

<script>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
export default {
  components: {
    Header,
    Footer
  }

}
</script>

<style>

</style>