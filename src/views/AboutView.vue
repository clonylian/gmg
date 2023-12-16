<template>
  <div class="about">
    <div class="cen">
      <div class="cen_1">
        <img  class="cen_gmg" src="../assets/2.png">
        <p class="cen_one">FULL WEBSITE COMING SOON</p>
        <div class="cen_2">
          <div><a target="_blank" href="https://t.me/genwealthgen">TELEGRAM</a></div>
          <div> <a target="_blank" href="https://twitter.com/genwealthgen">Twitter</a></div>
          <div> <a href="#">uniswap</a></div>
          <div @click="add"><a href="#" >Connect</a></div>
        </div>
        <div class="cen_3">
          <p class="cen_4">Accelerate your life with $GWG coin, your gateway to optimized gains. Leveraging breakthrough
            technology, we
            are here to fast-track your journey to financial freedom and unprecedented wealth. Your future, accelerated,
            with optimized gains — that is the $GWG mission.</p>
        </div>
        <div class="cen_5">
          <img src="../assets/3.gif">
        </div>
        <div class="cen_6">
          <p>
            Welcome to the era of accelerated life and optimized gains with the $GWG coin. Our groundbreaking platform is
            not just a technological marvel; it's your fastest route to a future brimming with wealth and financial
            freedom.
          </p>
          <p> 
            We leverage cutting-edge technology to offer you more than just gains; we offer optimized gains, amplifying
            your potential to generate wealth at an accelerated pace.
            Our mission is distinct and clear: to foster a world where financial growth is not just steady but
            accelerated, empowering you to reap the benefits of your investments in a timeframe that matches the speed of
            your dreams.
          </p>
          <p>
            We invite you to experience the transformative power of $GWG coin, a financial beacon designed to accelerate
            your life with optimized gains. Make the choice today to steer your financial journey towards a future where
            dreams are not just achieved, but accelerated.
          </p>
        </div>
        <div class="cen_7">
          <img src="../assets/4.jpg">
          <img src="../assets/5.jpg">
        </div>
        <div class="cen_8">
          <h1>EXPLORE THE $GWG UNIVERSE</h1>
          <div class="cen_9">
            <div class="cen_10">
              <p>Discover the technology that powers accelerated gains</p>
            </div>
            <div class="cen_10">
              <p>Learn about our steadfast commitment to fast-tracking your wealth generation journey</p>
            </div>
            <div class="cen_10">
              <p>Engage with a community focused on optimization and accelerated growth</p>
            </div>
            <div class="cen_10">
              <p>Invest in a future where your financial gains are not just assured, but optimized for speed and
                sustainability</p>
            </div>
          </div>
        </div>
        <div class="cen_11">
          <img src="../assets/6.png">
        </div>
      </div>
    </div>
    <audio autoplay preload="auto" src="../assets/DM_20230914160412_001.mp3"></audio>
    <p class="cen_12">Investors acknowledge and understand that $GWG Generational Wealth Generator tokens/coins have no intrinsic value, and their investment in $GWG is purely speculative. $GWG shall not be held liable for any loss of value or damages incurred by investors due to the lack of intrinsic value associated with the tokens/coins.</p>
  </div>
</template>   
<script>
export default{
  data(){
    return{

    }
  },
  methods:{
    add(){
      console.log(1111)
      main()
    }
  }
}

</script>
<style >
.about {
  width: 100%;
  height: auto;
  background-image: radial-gradient(circle closest-corner, rgba(0, 0, 0, .31), #fff), url(https://uploads-ssl.webflow.com/65027ee…/65027f2…_360_F_342016704_eDLeR4trtRfCdxhQ7yRLxJET9xFXGhtl.jpg);
  background-position: 0 0, 0 0;
}

.cen {
  width: 60%;
  margin: 0 auto;
  /* border: 1px red solid; */
}

.cen_1 {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.cen_gmg {
  width: 940px;
  height: 314px;
}

.cen_one {
  font-size: 55px;
  font-family: one;
  margin: 1rem 0 1rem 0;
}

.cen_2 {
  display: flex;
  margin-bottom: 5rem;
}

.cen_2>div {
  width: 10rem;
  border-radius: 15px;
  height: 2rem;
  margin: 0 auto;
  color: #000;
  text-align: center;
  line-height: 2rem;
  background-color: #fff;
  background-image: linear-gradient(rgba(0, 0, 0, .19), #fff);
  border-radius: 20px;
  margin-left: 17px;
  margin-right: 17px;
  padding: 20px 23px;
  font-family: one;
  font-size: 34px;
  transition: box-shadow .6s, background-color .4s;
  box-shadow: 0 12px 5px rgba(0, 0, 0, 0.2)
}

.cen_2>div>a {
  text-decoration: none;
  color: #000;
}

.cen_2>div:hover {
  color: #fff !important;
  background-color: #000;
  background-image: linear-gradient(rgba(0, 0, 0, .19), #fff);
  box-shadow: 0 20px 20px 20px rgba(0, 0, 0, .2);
}

.cen_3 {
  width: 80%;
  margin: 0 auto;
  font-family: one;
}

.cen_4 {
  font-size: 56px;
  text-align: center;
  line-height: 50px;
}

.cen_5 {
  margin: 3rem 0 4rem 0;
  /* width: 500px; */
  height: 455px;
}

.cen_6 {
  width: 80%;
  margin: 0 auto;
  font-family: one;
}

.cen_6>p {
  font-size: 56px;
  text-align: center;
  line-height: 50px;
  margin-bottom: 3rem;
}

.cen_7 {
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.cen_7>img:nth-child(1) {
  max-width: 1000px;
  width: 940px;
  height: 312px;
  border-radius: 15px;
  margin-bottom: 2rem;
}

.cen_7>img:nth-child(2) {
  max-width: 1000px;
  width: 940px;
  height: 940px;
  border-radius: 15px;
}

.cen_8 {
  font-family: one;
  font-size: 42px;
  margin-top: 5rem;
  margin-bottom: 1rem;
  text-align: center;
}

.cen_9 {
  width: 100%;
  display: flex;
  flex-direction: column;
}

.cen_9>div {
  border-radius: 20px;
  margin-top: 19px;
  padding: 87px;
  background-image: linear-gradient(rgba(0, 0, 0, .18), #fff);
  border-radius: 20px;
}

.cen_9>div>p {
  font-size: 53px;
}
.cen_11>img{
  width: 940px;
}
.cen_11{
  padding-bottom: 10rem;
}
.cen_12{
  text-align: center;
}
@media (max-width: 600px) {
  .cen_gmg{
    width: 414px;
    height: 138px;
  }
  .cen{
    width: 98%;
  }
  .cen_one {
    font-size: 50px;
    text-align: center;
    font-weight: 900;
    margin-bottom: 3rem;
  }
  .cen_2{
    flex-direction: column
  }
  .cen_2>div{
    margin-bottom: 2rem;
  }
  .cen_7>img:nth-child(1) {
    width: 414px;
    height: 140px;
  }
  .cen_7>img:nth-child(2) {
    width: 414px;
    height: 414px;
  }
  .cen_11>img{
    width: 414px;
    height: 140px;
  }
  .cen_9>div>p {
    font-size: 24px;
  }
  .cen_9>div{
    padding: 2rem;
  }
  .cen_5>img{
    width: 398px;
  }
  .cen_6>p {
    font-size: 20px;
    text-align: center;
    line-height: 20px;
    margin-bottom: 3rem;
  }
  .cen_8{
    font-size: 24px;
  }
  .cen_4 {
    font-size: 22px;
    line-height: 25px;
    /* height: 20px; */
  }
}
</style>
