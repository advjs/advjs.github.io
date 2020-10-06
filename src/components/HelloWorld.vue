<template>
  <h1>{{ msg }}</h1>
  <h2>面向未来前端的 ADV 文字冒险游戏引擎</h2>
  <h3>{{ slogan }}</h3>
  <a href="https://adv.yunyoujun.cn/docs/" target="_blank">
    <button class="zi-btn">Docs</button>
  </a>
  <a href="https://github.com/YunYouJun/adv" target="_blank">
    <button class="zi-btn primary">
      GitHub
      <i class="prefix zi-icon-github"></i>
    </button>
  </a>
  <a href="https://adv.yunyoujun.cn/parser/" target="_blank">
    <button class="zi-btn">Parser</button>
  </a>
  <h3 style="margin-top: 3rem">愿能在未来的冒险中，与你相遇</h3>
  <a href="https://adv.yunyoujun.cn" target="_blank"
    ><button class="zi-btn success">预览</button>
  </a>
  <h3 style="margin-top: 2rem">开发中，敬请期待</h3>
  <h3>...</h3>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
    return {
      slogan: "像写小说一样制作 ADV",
    };
  },
};
</script>

<style>
button {
  margin: 5px;
}
</style>
