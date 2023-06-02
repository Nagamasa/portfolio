<script setup lang="ts">
const props = defineProps({
  title: {
    type: String,
    default: ""
  },
  sentence: {
    type: String,
    default: ""
  },
  substance: {
    type: String
  },
  language: {
    type: String
  },
  framework: {
    type: String
  },
  db: {
    type: String
  },
  versioncontrol: {
    type: String
  },
  other: {
    type: String
  }
})
</script>
<template>
    <div class="leaf-row">
      <h2>{{ title }}</h2>
      <h3 class="leaf-card"> 
        <div>{{ sentence }}</div>
        <div>{{ substance }}</div> 
        <div>{{ language }}</div> 
        <div>{{ framework }}</div> 
        <div>{{ db }}</div> 
        <div>{{ versioncontrol }}</div> 
        <div>{{ other }}</div> 
      </h3>
    </div>
</template>
<style scoped>
h2 {
  color: rgb(19, 20, 20);
  width: 200px;
}
.tree-container {
  margin-left: 150px;
}
.leaf-row {
  display: flex;
}
.leaf-card {
    width: 75%;
    left: 25%;
    padding: 15px 30px;
    margin-bottom: 10px;
    background-color: rgb(26 27 33 / 80%);
    border: 5px solid rgb(191, 199, 199);
    text-shadow: 1px 1px 1px rgb(26 27 33 / 80%);
    color: rgba(255,255,255,.9);
}
</style>