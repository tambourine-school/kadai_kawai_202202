<!--HTML-->
<template>
	<div>
     <AppHeader />

      <main>
       <img class="top" src="/images/3_2.jpg" alt="">

       <div class="p-top-intro">
        <p class="p-top-intro_txt">
          テキストテキストテキスト
        <br>
          テキストテキストテキスト
        <br>
          テキストテキストテキスト
        </p>
        <p class="p-top-intro_txt">
          テキストテキストテキスト
        <br>
          テキストテキストテキスト
        <br>
          テキストテキストテキスト
        </p>
        <p class="p-top-intro_txt">
          テキストテキストテキスト
        <br>
          テキストテキストテキスト
        <br>
          テキストテキストテキスト
        </p>
       </div>
<!--おしらせ-->
        <img class="img" src="/images/top_news_ttl.jpg" alt="">
  
       <div class="p-tp-news_list u-dp-flex">
         <div class="p-tp-news_item"> 
            <img src="/images/2022-270x200.jpg" alt="">
            <h3 class="p-tp-news_ttl">テキスト</h3>
            <p class="p-tp-news_data">テキスト</p>
         </div>
         <div class="p-tp-news_item"> 
            <img src="/images/036-270x200.jpg" alt="">
            <h3 class="p-tp-news_ttl">テキスト</h3>
            <p class="p-tp-news_data">テキスト</p>
         </div>
         <div class="p-tp-news_item"> 
           <img src="/images/ae46b1f460ee46f789c27b264a6cb421-270x200.jpg" alt="">
           <h3 class="p-tp-news_ttl">テキスト</h3>
           <p class="p-tp-news_data">テキスト</p>
         </div>
         <div class="p-tp-news_item"> 
           <img src="/images/2-1-270x200.jpg" alt="">
           <h3 class="p-tp-news_ttl">テキスト</h3>
           <p class="p-tp-news_data">テキスト</p>
         </div>
       </div>
        <p class="c-btn-set">
        <nuxt-link to="https://sora-pac.com/news/">おしらせ一覧へ</nuxt-link>
        </p>
<!--撮影プラン-->
        <img class="img" src="/images/top_plan_ttl.jpg" alt="">

      </main>

      <AppFooter />
	</div>
</template>

<!--javascript-->
<script>
export default {
}
</script>

<!--CSS-->
<style scoped>
@media screen and (max-width: 600px) {}
</style>