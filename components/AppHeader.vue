<template>
  <div>
    <header id="index" class="index">
     <h1 class="l-header__logo"> <nuxt-link to="https://sora-pac.com/">	<img src="/images/logo_sp.png" alt="SORA PHOTO SORADOMARI">
     </nuxt-link> </h1>
     <nav id="l-header-nav_list">
         <ul class="l-header_list">
             <li>
                 <nuxt-link to="https://sora-pac.com/abouts/">わたしたちのこと</nuxt-link>
             </li>
             <li>
                 <nuxt-link to="https://sora-pac.com/studio/">スタジオのこと</nuxt-link>
             </li>
             <li>
                 <nuxt-link to="https://sora-pac.com/plan/">撮影プラン</nuxt-link>
             </li>
             <li>
                 <nuxt-link to="https://sora-pac.com/stay/">ご宿泊</nuxt-link>
             </li>
             <li>
                 <nuxt-link to="https://sora-pac.com/voice/">お客さまの声</nuxt-link>
             </li>
             <li>
                 <nuxt-link to="https://sora-pac.com/news/">おしらせ・ブログ</nuxt-link>
             </li>
         </ul>
     </nav>
     <p class="l-header_tel"> 
         <nuxt-link to="tel:090-1365-****">090-1365-****</nuxt-link>
     </p>
     <div class="l-header_lang">
         <ul class="l-header-lang_list u-dp-flex">
             <li class="l-header-lang_item is-current"><nuxt-link to="https://sora-pac.com/">JP</nuxt-link></li>
             <li class="l-header-lang_item"><nuxt-link to="#">EN</nuxt-link></li>
         </ul>
      </div>
      <p class="l-header_icon"> 
          <nuxt-link to="https://www.instagram.com/sora_photo_and_cinema/" target="_blank">
          <img src="https://sora-pac.com/wp/wp-content/themes/site/images/ico_insta.svg" alt="instagram">
         </nuxt-link> 
      </p>

    </header>
    
  </div>
</template>