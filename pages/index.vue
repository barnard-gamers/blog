<template>
  <div class="main">
    <div class="top">
      <img class="barnard-img" src="~/assets/comet.svg" alt="">
      <div class="barnard-title">Barnard</div>
      </div>
    <div class="info">
      <li>一緒にゲームをしたい人を探してる人は是非❗</li>
      <iframe src="https://discordapp.com/widget?id=498488382226300958&theme=dark" width="350" height="500" allowtransparency="true" frameborder="0"></iframe>   
      <ul class="bot-info">
        <li><span class="barnard">Branard</span>ではより楽しくゲームをプレイするために</li>
        <li>様々なボットが稼働しています。</li>
        <li>ボットたちの使い方と紹介は<nuxt-link class="barnard" to="./bot_about">こちら</nuxt-link></li>
      </ul>   
    </div> 
  </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.bot-info{
  width: 900px;
  padding: 0;
  margin: 0 auto;
}

.barnard{
  color: #E74C3C;
}
.barnard-img{
  margin-top: 120px;
  height: 350px;
  width: 350px;
}
.barnard-title{
  color: #E74C3C;
  font-size: 110px;
}
body{
  margin: 0;
  background-color: #212121;
}
ul{
  list-style: none;
}
.main{
  font-family: YuGothic,'Yu Gothic','Hiragino Kaku Gothic ProN','ヒラギノ角ゴ ProN W3',sans-serif;
  max-width: 1240px;
  margin: 0 auto;
}
.info{
  font-size: 35px;
  list-style: none;
  text-align: center;
  color: white;
}
.top{
  height: 800px;
  text-align: center;
  background-color: #212121;
}
</style>

