<template>
  <div>
    <AppHeader />
    
   <div class="top">
     <img src="/images/3_2.jpg" alt="">
   </div>

<!--コンセプト-->
   <div class="con">
     <p class="txt">
       目を閉じて、思い出してみる。
       <br>
       生まれてすぐのほわほわの髪の毛や、
       <br>
       ぎゅっとした手、おちそうなほっぺ。
       <br>
       おっぱいのにおい。
     </p>
     <p class="txt">
       ふり返ると、ふっと笑みがこぼれて、
       <br>
       じんわり涙がにじんだり、
       <br>
       胸がぎゅーっとなる写真。
     </p>
     <p class="txt">
       愛しいたくさんの時間がつまっていて、
       <br>
       空気やにおいや声や音までも蘇ってくる、
       <br>
       そんな写真を残すお手伝いをしたいです。
     </p>
   </div>

<!--おしらせ-->
   <div class="news">
     <div class="news_img">
       <img src="/images/top_news_ttl.jpg" alt="">
     </div>
     <section>
       <nuxt-link to=""><img src="/images/2022-270x200.jpg" alt=""></nuxt-link>
       <h1>2022*</h1>
       <h2>2022.01.01</h2>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/2022-270x200.jpg" alt=""></nuxt-link>
       <h1>撮影会のおしらせ</h1>
       <h2>2021.09.09</h2>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/2022-270x200.jpg" alt=""></nuxt-link>
       <h1>ホームページリニューアルのおしらせ</h1>
       <h2>2021.07.27</h2>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/2022-270x200.jpg" alt=""></nuxt-link>
       <h1>宇美八幡宮に安産祈願に行ってきました</h1>
       <h2>2021.07.20</h2>
     </section>
     <div class="btn_style">
       <nuxt-link to="" class="btn">おしらせ一覧へ</nuxt-link>
     </div>
    </div>


<!--撮影プラン-->
   <div class="plan">
     <div class="plan_img">
       <img src="/images/top_plan_ttl.jpg" alt="">
     </div>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>マタニティフォト</h3>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>赤ちゃん</h3>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>お宮参り</h3>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>1才おたんじょうび</h3>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>七五三</h3>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>入園・入学</h3>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>バースデー</h3>
     </section>
     <section>
       <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
       <h3>家族写真</h3>
     </section>
     <div class="btn_style">
       <nuxt-link to="" class="btn">詳しくはこちら</nuxt-link>
     </div>
   </div>
  
<!--ご宿泊-->
   <div class="stay">
     <div class="stay_img">
       <img src="/images/top_stay_ttl.jpg" alt="">
     </div>
     <div class="stay_img2">
       <img src="/images/top_stay_img_pc.jpg" alt="">
     </div>
     <h4>SORADOMARI</h4>
     <h5>“泊まれる写真屋さん”</h5>
     <p class="txt2">
       ここちよい風でのんびりうたたね。
       <br>
       おもいきり深呼吸をして、自然の声に耳をかたむける。
       <br>
       家族で過ごす、少しだけ非日常の時間。
       <br>
       1日1組限定の完全貸切で安心してご宿泊いただけます。
       <br>
       ご家族でのんびりお楽しみください。
     </p>
     <div class="btn_style">
       <nuxt-link to="" class="btn">詳しくはこちら</nuxt-link>
     </div>
   </div>

<!--お客さまの声-->
   <div class="voice"> 
     <div class="voice_img">
       <img src="/images/top_voice_ttl.jpg" alt="">
     </div>
     <section>
       <hooper>
         <slide>
           <nuxt-link to=""><img src="/images/1-340x340.jpeg" alt=""></nuxt-link>
           <h5>七五三</h5>
           <h6>北九州市</h6>
           <h6 class="sab">S様  出張撮影</h6>
           <p class="voice_txt">あの日の息子の晴れ姿を、家族の笑顔を沢山の写真に 収めて頂いて、大満足しております。・・・</p>
         </slide>
         <slide>
           <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
           <h5>マタニティフォト</h5>
           <h6>大分県</h6>
           <h6 class="sab">T様：公園</h6>
           <p class="voice_txt">素敵な写真、届きました。・・・</p>
         </slide>
         <slide>
           <nuxt-link to=""><img src="/images/top_plan_img01.jpg" alt=""></nuxt-link>
           <h5>家族写真</h5>
           <h6>北九州市</h6>
           <h6 class="sab">S様：海</h6>
           <p class="voice_txt">ホームページに掲載された心温まる写真を見て、即決でした。・・・</p>
         </slide>
         <hooper-pagination slot="hooper-addons"></hooper-pagination>
       </hooper>     
     </section>
     <div class="btn_style">
       <nuxt-link to="" class="btn">もっと見る</nuxt-link>
     </div>
   </div>

<!--インスタグラム-->
   <div class="insta">
     <div class="insta_img">
       <img src="/images/top_insta_ttl.jpg" alt="">
     </div>
     <div>
       <nuxt-link to=""><img src="/images/270259345_134957148968740_8815768267127808531_nfull.jpg" alt=""></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/270259345_134957148968740_8815768267127808531_nfull.jpg" alt=""></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/270259345_134957148968740_8815768267127808531_nfull.jpg" alt=""></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/270259345_134957148968740_8815768267127808531_nfull.jpg" alt=""></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/270259345_134957148968740_8815768267127808531_nfull.jpg" alt=""></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/270259345_134957148968740_8815768267127808531_nfull.jpg" alt=""></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/270259345_134957148968740_8815768267127808531_nfull.jpg" alt=""></nuxt-link>
     </div>
     <div class="btn_insta">
     <nuxt-link to="" class="btn_insta2">More...</nuxt-link>
     </div>
   </div>

<!--Googleマップ-->
   <div class="map">
     <img src="/images/452AC94C-FD85-4CE5-A110-E74303596798.png" alt="">
   </div>

<!--最後の画像-->
   <div class="end">
     <div>
       <nuxt-link to=""><img src="/images/btn01.jpg" alt="わたしたち"></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/btn01.jpg" alt="スタジオ"></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/btn01.jpg" alt="撮影"></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/btn01.jpg" alt="ご宿泊"></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/btn01.jpg" alt="お客様"></nuxt-link>
     </div>
     <div>
       <nuxt-link to=""><img src="/images/btn01.jpg" alt="おしらせ"></nuxt-link>
     </div>
   </div>

    <AppFooter />

  </div>
</template>

<script>
import {
  Hooper,
  Slide,
  Pagination as HooperPagination,
  Navigation as HooperNavigation,
} from 'hooper'
import 'hooper/dist/hooper.css'
export default {
  components: {
    Hooper,
    Slide,
    HooperPagination,
    HooperNavigation,
  }
}
</script>

<style scoped>

::after, ::before {
    box-sizing: border-box;
    text-align: center;
}

.hooper-slide {
  padding: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  border: 2px solid #fff;
  font-size: 30px;
}

</style>