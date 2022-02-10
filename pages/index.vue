<!--HTML-->
<template>
	<div>
     <AppHeader />

     <main>
       <img class="top" src="/images/3_2.jpg" alt="">
<!--コンセプト-->
      <div class="p-cont-inner">
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
       <section class="p-tp-news js-tp-news is-animated fadeInUp">
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
       </section>
<!--撮影プラン-->
       <section class="p-tp-plan js-tp-plan is-animated fadeInUp">
        <img class="img" src="/images/top_plan_ttl.jpg" alt="">
       <div class="p-tp-plan_list u-dp-flex">
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img01.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/maternity/">マタニティフォト</nuxt-link></h3>
         </div> 
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img02.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/baby/">赤ちゃん</nuxt-link></h3>
         </div> 
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img03.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/omiyamairi/">お宮参り</nuxt-link></h3>
         </div> 
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img04.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/firstbirth/">1才おたんじょうび</nuxt-link></h3>
         </div> 
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img05.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/753plan/">七五三</nuxt-link></h3>
         </div> 
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img06.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/admission/">入園・入学</nuxt-link></h3>
         </div> 
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img07.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/birthday/">バースデー</nuxt-link></h3>
         </div> 
         <div class="p-tp-plan_item">
           <img src="/images/top_plan_img08.jpg" alt="">
           <h3 class="p-tp-plan_txt">
           <nuxt-link to="https://sora-pac.com/plan/family/">家族写真</nuxt-link></h3>
         </div> 
         <p class="c-btn-set">
            <nuxt-link to="https://sora-pac.com/plan/">詳しくはこちら→</nuxt-link>
         </p>
       </div>
       </section>
      </div>
<!--ご宿泊-->
      <div class="p-tp-stay js-tp-stay is-animated fadeInUp">
       <img class="img" src="/images/top_stay_ttl.jpg" alt="">

      </div>
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