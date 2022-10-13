<script setup>
import Carousel from "./my_components/Carousel.vue"
import Navigation from './my_components/Navigation.vue'
import PostBody from "./my_components/PostBody.vue";


</script>

<template>
  <header>
    <Navigation/>
  </header>

  <main>
    <el-row>
      <el-col :span="12" :offset="6">
        <Carousel item="1"/>
      </el-col>
    </el-row>
    <PostBody>

    </PostBody>
  </main>
</template>

<style scoped>
</style>
