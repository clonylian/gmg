<template>
  <div class="hello">
    <div class="box">
      <h1>ARE U RDY FOR GENERATIONAL WEALTH?</h1>
      <div class="dian">
        <p >
          <a  href="https://gmg-zeta.vercel.app/#/about"  style="color: black;" >
            YES, RETARD
          </a>
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {

  },
  methods: {
    to() {
      this.$router.push('/about');
    },
 
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@font-face {
  font-family: 'one';
  /* 自定义字体名称 */
  src: url('../assets/one.ttf') format('woff2'),
    /* 字体文件路径和格式 */
}

* {
  text-decoration: none;
}

.hello {
  width: 100%;
  height: 100%;
  // background-image: url('../assets/1.jpg');
}

.box {
  width: 100%;
  height: 100%;
}

.box>h1 {
  max-width: 1200px;
  color: #000;
  text-align: center;
  margin-top: 153px;
  font-size: 145px;
  line-height: 1;
  font-family: one;
  margin: 8rem auto;
}

.dian {
  width: 100%;
  display: flex;
  justify-content: center
}

.dian>p {
  width: 12rem;
  border-radius: 15px;
  height: 3rem;
  margin: 0 auto;
  color: #000;
  text-align: center;
  line-height: 3rem;
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

.dian>p:hover {
  color: #fff;
  background-color: #000;
  background-image: linear-gradient(rgba(0, 0, 0, .19), #fff);
  box-shadow: 0 20px 20px 20px rgba(0, 0, 0, .2);
}

@media (max-width: 600px) {
  .box>h1 {
    font-size: 70px;
    margin: 6rem auto;
  }

  .dian>p {
    width: 10rem;
    border-radius: 15px;
    height: 2.5rem;
    margin: 0 auto;
    color: #000;
    text-align: center;
    line-height: 2.5rem;
    background-color: #fff;
    background-image: linear-gradient(rgba(0, 0, 0, 0.19), #fff);
    border-radius: 20px;
    margin-left: 17px;
    margin-right: 17px;
    padding: 20px 23px;
    font-family: one;
    font-size: 34px;
    transition: box-shadow 0.6s, background-color 0.4s;
    box-shadow: 0 12px 5px rgba(0, 0, 0, 0.2);
  }

}</style>
