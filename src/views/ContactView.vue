<template>
  <div class="container">
    <div class="text-area">
      <div>
        <p>Name ※</p>
        <input class="input-style name-text">
      </div>
      <div>
        <p>Email Address ※</p>
        <input class="input-style mail-text">
      </div>
      <div>
        <p>Message ※</p>
        <textarea class="input-style message-text"></textarea>
      </div>
    </div>
    <div>
      <button type="button">送信</button>
    </div>
  </div>
</template>
<script setup lang="ts">
</script>
<style scoped>
.container {
  margin-left: 40%;
}
.text-area {
  margin-bottom: 15px;
}
.name-text{
  height: 40px;
}
.mail-text{
  height: 40px;
}
.message-text{
  height: 200px;
  white-space: pre-wrap;
}
.input-style {
  width: 450px;
  border-radius: 5px;
  border: solid 2px;
  margin-bottom: 10px;
  font-family: sans-serif;
}
</style>