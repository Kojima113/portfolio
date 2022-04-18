<template>
  <div>
    <h1>ポートフォリオ</h1>
    <h2>自己紹介</h2>
    <div class="matome">
      <h3>名前</h3>
      <p>小島大輝</p>
    </div>
    <div class="matome">
      <h3>生年月日</h3>
      <p>2000年1月4日</p>
    </div>
    <h2>参加したゲーム作品</h2>
    <a href="http://pandd.sakura.ne.jp/game.html" target="_blank" rel="noopener">参加サークルのゲーム一覧ページ</a>
    <div class="matome">
      <h3>ミサイルP</h3>
      <p>遊園地とかでよく見るレースゲームに想いを馳せながら作られたゲーム</p>
    </div>
    <div class="matome">
      <h3>お前らを全員プリンにしてやるの</h3>
      <p>開始位置とゴール位置が決められており、マスを回転させて自機をゴールに導くパズルゲーム</p>
    </div>
    <div class="matome">
      <h3>ノエルのクリスマス☆アドベンチャー</h3>
      <p>弾幕STGゲーム  グラフィッカで参加</p>
    </div>
  </div>
</template>

<script>
export default {
  name: `Top`,
};
</script>

<style scoped>
h3 {
  display: inline-block;
  margin: 10px 10px;
}
p {
  display: inline-block;
  margin: 0 10px;
}
#matome {
  display: block;
}
</style>