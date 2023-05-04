<template>
  <div>
    <main>
      <section class="hero">
        <h1><img src="/assets/images/logo01.png" alt="NIKKEI VR"></h1>
        <div class="btn">
          <figure class="btn_apple"><a href="#" target="_blank"><img
                src="/assets/images/btn_apple.png" alt="App Store"></a></figure>
          <figure class="btn_google"><a
              href="#" target="_blank"><img
                src="/assets/images/btn_google.png" alt="Google Play"></a></figure>
        </div>
      </section>
      <!-- /.hero -->

      <!--slide_area-->
      <section class="slide_area">
        <div class="contentWidth">
          <div class="slide_contents">
            <div class="txt_area">
              <img src="/assets/images/index_slide_ttl.png" alt="" class="pc">
              <img src="/assets/images/index_slide_ttl_sp.png" alt="" class="sp">
            </div>
            <div class="slick_area" id="car-slider">
              <div class="swiper carapp">
                <div class="swiper-wrapper">
                  <div class="swiper-slide"> 
                    <img src="/assets/images/index_slide07_bg.jpg" alt class="pc">
                    <img src="/assets/images/index_slide07_bg_sp.jpg" alt class="sp">
                  </div>
                  <div class="swiper-slide"> 
                    <img src="/assets/images/index_slide06_bg.jpg" alt class="pc">
                    <img src="/assets/images/index_slide06_bg_sp.jpg" alt class="sp">
                  </div>
                  <div class="swiper-slide"> 
                    <img src="/assets/images/index_slide02_bg.jpg" alt class="pc">
                     <img src="/assets/images/index_slide02_bg_sp.jpg" alt class="sp"></div>
                  <div class="swiper-slide"> 
                    <img src="/assets/images/index_slide03_bg.jpg" alt class="pc">
                    <img src="/assets/images/index_slide03_bg_sp.jpg" alt class="sp">
                    </div>
                </div>
                <div class="swiper-pagination"></div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!--/slide_area-->

      <section class="main01">
        <div class="main-inner">
          <div class="sentence-area">
            <h2>360°動画やイメージで<br>現場の臨場感を体験</h2>
            <figure class="sp"><img src="/assets/images/img01-sp.png" alt="スマートフォン表示"></figure>
            <p>文章からは読み取れなかった情報を、360°映像の中で発見できるかもしれません。まさに、現場にいるかのような臨場感を味わっていただけます。</p>
          </div>
          <div class="figure-area">
            <figure class="pc"><img src="/assets/images/img01.png" alt="スマートフォン表示"></figure>
          </div>
        </div>
      </section>
      <!-- /.main01 -->

      <section class="main02">
        <div class="main-inner">
          <div class="sentence-area">
            <h2> VRミュージアムで<br>これまでになかった<br>新しい美術鑑賞を</h2>
            <figure class="sp"><img src="/assets/images/img02-sp.png" alt="スマートフォン表示"></figure>
            <p>自分のぺースで好きな時に好きなだけ、VRミュージアム内を歩いてアート作品をお楽しみください。日本経済新聞社主催の美術展などのアート作品をご鑑賞いただけます。*近日公開予定</p>
          </div>
          <div class="figure-area">
            <figure class="pc"><img src="/assets/images/img02.png" alt="スマートフォン表示"></figure>
          </div>
        </div>
      </section>
      <!-- /.main02 -->

      <section class="main03">
        <div class="main-inner">
          <div class="sentence-area">
            <h2>全く新しいニュースアプリを<br>体感したい方へ</h2>
            <figure class="sp"><img src="/assets/images/img03-sp.png" alt="スマートフォン表示"></figure>
            <p>ニュース記事の情報をより深く理解したい方や、アート作品に興味がある方、最新のコンテンツを体験したい方など、いつも使っているニュースアプリとは異なる新しいニュースアプリを体感してみたい方におすすめです。</p>
          </div>
          <div class="figure-area">
            <figure class="pc"><img src="/assets/images/img03.png" alt="スマートフォン表示"></figure>
          </div>
        </div>
      </section>
      <!-- /.main03 -->

      <section class="download">
        <h2><img src="/assets/images/logo02.png" alt="NIKKEI VR"></h2>
        <h3>日経VRのダウンロードはこちら</h3>
        <div class="btn">
          <figure class="btn_apple"><a href="#" target="_blank"><img
                src="/assets/images/btn_apple.png" alt="App Store"></a></figure>
          <figure class="btn_google">
            <a href="#" target="_blank">
              <img src="/assets/images/btn_google.png" alt="Google Play"></a>
            </figure>
        </div>
      </section>
      <!-- /.download -->
    </main>
  </div>
</template>

<script>
export default{ 
mounted(){
  var swiper = new Swiper(".carapp", {
    loop:true,
    pagination: {
      el: ".swiper-pagination",
      clickable:true,
    },
  });
}
}
</script>
<style>
#car-slider .swiper-pagination-bullet{
  background: #fff;
  opacity: 1;
  height: 10px;
  width: 10px;
}

#car-slider .swiper-pagination-bullet.swiper-pagination-bullet-active{
  background: #b6a777;
}
.swiper-pagination{
  position: relative;
  top: 5px !important;
}
</style>