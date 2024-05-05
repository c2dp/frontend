<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
// import AddForm from './components/AddForm.vue'
// import ShowTable from './components/ShowTable.vue'
// import BaseLayout from './components/layout/BaseLayout.vue'
import ShowButton from './plugins/ShowButton.vue'
import UploadFile from './plugins/UploadFile.vue'
</script>

<template>
  <el-divider content-position="left">插件</el-divider>
  <el-divider />
  <main>
    <el-divider content-position="left">Button</el-divider>
    <ShowButton />
    <el-divider content-position="left">Upload</el-divider>
    <UploadFile />
  </main>
  <el-divider />
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
