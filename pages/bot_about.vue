<template>
  <div class="main">
    <div class="top">
      <img class="barnard-img" src="~/assets/comet.svg" alt="">
      <div class="barnard-title">Barnard Bots</div>
      </div>
    <ul class="bots">
      <div class="bot-about">
        <img class="bot-img" src="~/assets/pantheon-dragonslayer.png" alt="">
        <ul>
          <li>おそらく皆さん最初に目にするbot</li>
          <li><span class="barnard">Barnard</span>の秩序を保つ門番Pantheon君</li>
          <li>彼は入って来た人に規約を提示する</li>
          <li>シンプルなボット少し面倒かもしれないけど</li>
          <li>同意してね</li>
        </ul>
      </div>
      <div class="bot-about">
        <img class="bot-img" src="~/assets/ryze-professor.png" alt="">
        <ul>
          <li>彼は、様々な国籍の人がいる</li>
          <li><span class="barnard">Barnard</span>にとっては重要な存在Ryze先生</li>
          <li>日本語、英語、韓国語、中国語</li>
          <li>の４言語を翻訳してくれるぞただし</li>
          <li>少し使い方が難しいので!rzで説明が出る</li>
          <li>それを見て使ってみよう</li>
        </ul>
      </div>
      <div class="bot-about">
        <img class="bot-img" src="~/assets/twisted-fate-pulsefire.png" alt="">
        <ul>
          <li>Twisted FateはLOLに関するボット</li>
          <li>サモナーネームを入れることで</li>
          <li>そのサモナーのマスタリーが高い</li>
          <li>チャンピオンを教えてくれるぞ</li>
          <li>.helpで説明を見てみよう</li>
        </ul>
      </div>
      <div class="bot-about">
        <img class="bot-img" src="~/assets/teemo-beemo.png" alt="">
        <ul>
          <li>ヘイトが高いであろうTeemo</li>
          <li>彼もLOLに関するボット</li>
          <li>彼はとってもシンプルなボット</li>
          <li>.teemoと打つだけでランダムなチャンピオン</li>
          <li>を提供してくれるop.ggも出してくれるので</li>
          <li>使いたいチャンピオンがない時にでも使おう</li>
        </ul>
      </div>
    </ul>
  </div>
</template>

<style>
.bot-img{
  width: 170px;
  height: 170px;
  border-radius: 85px;
}
.bot-about{
  margin-top: 100px;
  display: inline-flex;
  font-family: YuGothic,'Yu Gothic','Hiragino Kaku Gothic ProN','ヒラギノ角ゴ ProN W3',sans-serif;
  font-size: 35px;
  list-style: none;
  text-align: left;
  color: white;
}
</style>

