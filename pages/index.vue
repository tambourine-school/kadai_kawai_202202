<!--HTML------------------------------------------------------------>
<template>
	<div>
     <AppHeader />

      <main>
       <h1 class="l-header__logo"> <nuxt-link to="https://sora-pac.com/">	<img src="https://sora-pac.com/wp/wp-content/themes/site/images/logo.svg" alt="SORA PHOTO SORADOMARI">
       </nuxt-link> </h1>

       <img class="top" src="/images/3_2.jpg" alt="">

       <div class="txt">
        <p>テキストテキストテキスト
        <br>テキストテキストテキスト
        <br>テキストテキストテキスト
        <br>テキストテキストテキスト
        <br>テキストテキストテキスト
        <br>テキストテキストテキスト
        <br>テキストテキストテキスト
        </p>
       </div>
      <!--おしらせ------>
        <img class="img" src="/images/top_news_ttl.jpg" alt="">
        <br>
       <div class="nakami">
        <img src="/images/2022-270x200.jpg" alt="">
        <h3 class="daimei">テキスト</h3>
        <p class="sabu">テキスト</p>
        <img src="/images/036-270x200.jpg" alt="">
        <h3 class="daimei">テキスト</h3>
        <p class="sabu">テキスト</p>
        <img src="/images/ae46b1f460ee46f789c27b264a6cb421-270x200.jpg" alt="">
        <h3 class="daimei">テキスト</h3>
        <p class="sabu">テキスト</p>
        <img src="/images/2-1-270x200.jpg" alt="">
        <h3 class="daimei">テキスト</h3>
        <p class="sabu">テキスト</p>
       </div>
        <p class="ichiran">
        <nuxt-link to="https://sora-pac.com/news/">おしらせ一覧へ</nuxt-link>
        </p>
      <!--撮影プラン----->
        <img class="img" src="/images/top_plan_ttl.jpg" alt="">

      </main>

      <AppFooter />
	</div>
</template>

<!--javascript------------------------------------------------------>
<script>
export default {
}
</script>

<!--CSS------------------------------------------------------------->
<style scoped>
</style>