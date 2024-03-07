<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <div class="background-wrapper">
    <h1>李小白</h1>
    <div class="content-wrapper">
      <div class="left">
        <img src="./assets/au.jpeg" />
      </div>
      <div>
        <h2 class="center">天初暖，日初长，好春光</h2>
        <br />
        <div class="item">
          <div>关于我</div>
          <div>作品集</div>
        </div>
        <div class="item">
          <div>合作</div>
          <div>博客</div>
        </div>
        <div class="item">
          <div>评论</div>
          <div>联系我</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.background-wrapper {
  width: 100%;
  height: 100%;
  background: #8b97fd;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.background-wrapper h1 {
  padding-bottom: 40px;
}

.content-wrapper {
  display: flex;
  width: 100%;
}

.left {
  width: 50vw;
  display: flex;
  justify-content: flex-end;
  padding-right: 5%;
}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.item {
  display: flex;
}

.item div {
  width: 200px;
  background: #6872d1;
  margin: 20px;
  height: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
