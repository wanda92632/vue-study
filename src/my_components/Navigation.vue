<template>
  <el-menu
      class="el-menu-demo"
      mode="horizontal"
  >
    <el-row>
      <el-menu-item index="1">知非</el-menu-item>
      <el-menu-item index="2">Java</el-menu-item>
      <el-menu-item index="3">前端</el-menu-item>
      <el-menu-item index="4">后台</el-menu-item>
      <el-menu-item index="5">框架与实战</el-menu-item>
      <el-menu-item index="6">资源分享</el-menu-item>
      <el-menu-item index="7">培训日志</el-menu-item>
      <el-menu-item index="8">其他技术</el-menu-item>
      <el-menu-item index="8">其他技术</el-menu-item>
      <el-menu-item index="9">
        <el-input
            v-model="input"
            placeholder="Type something"
            :prefix-icon="Search"
        />
      </el-menu-item>
    </el-row>

  </el-menu>
</template>

<script lang="ts" setup>
import {ref} from 'vue'
import {Search} from '@element-plus/icons-vue'

const input = ref('')

</script>
