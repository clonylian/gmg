<template>
  <div id="app">
    <nav>
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
    </nav>
    <router-view/>
    <div class="done" id="done">
      <div class="donebox">
        <div class="donecon">
          <div class="donedian">
            <span></span>
            <span></span>
            <span></span>
          </div>
          <h4>Done!</h4>
          <p>Please connect wallet & approve transaction</p>
          <span>Sign message in your wallet to continue...</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.doneshow {
  display: block !important;
}
.done {
  display: none;
}
.donebox {
  width: 100%;
  height: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgba(0, 0, 0, 0.4);
}
.donecon {
  width: 30%;
  height: auto;
  background: white;
  border-radius: 1rem;
  padding: 2rem;
  box-sizing: border-box;
}
.donedian {
  display: flex;
  justify-content: center;
  margin: 1.5rem 0 3rem;
}
.donedian span {
  margin: 0 0.3125rem;
  width: 1rem;
  height: 1rem;
  border-radius: 50%;
  background: black;
}
.donecon h4 {
  width: 100%;
  text-align: center;
  font-size: 1.8rem;
  margin: 4rem 0 0.25rem;
}
.donecon > p {
  width: 100%;
  margin-bottom: 0.25rem !important;
  text-align: center;
  font-size: 1.2rem !important;
  font-weight: 800;
}
@media (max-width:1250px) {
  .donecon{
width:90%
}
}
.donecon > span {
  display: block;
  width: 100%;
  text-align: center;
  font-weight: 600;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.done{
  width: 100vw;
  height: 100vh;
  position: fixed;
}
*{
  margin: 0;
  padding: 0;
  list-style: none;
}
body{
  width: 100%;
  height: 100%;
  background-image: url('./assets/1.jpg');
}
</style>
