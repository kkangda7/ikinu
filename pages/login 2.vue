<template>
  <div class="login">
    <div class="login__title">ikinuki</div>
    <ul class="login__form">
      <li>
        <div class="login__form__title">
          メールアドレス
        </div>
        <div class="login__form__input">
          <input type="text" placeholder="メールアドレス" />
        </div>
      </li>
      <li>
        <div class="login__form__title">
          パスワード
        </div>
        <div class="login__form__input">
          <input type="password" placeholder="パスワード" />
        </div>
      </li>
    </ul>
    <div  class="login__passwordForget">
      <a href="#">パスワードを忘れた方</a>
    </div>
    <div class="login__action">
      <button class="btn btn--large btn--submit">ログイン</button>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>