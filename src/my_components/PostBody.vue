<template>
  <el-row>
    <el-col :span="12" :offset="6">
      <el-row>
        HelloWorld
      </el-row>
      <el-row>
        撒飒飒的asd啊实打实打单；拉斯柯达laskdlasdl；as了看了撒累死了ask；来的阿拉山口了
      </el-row>
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: "PostBody"
  ,
  created() {
    let result;
    this.axios.get("/api/test/zhihu")
        .then(function (res) {
          result = res;
          console.log(result);
        }).catch(function (error) {
      console.log(error)
    });
  },
  data() {
    return {
      count: 1
    }
  },

  // `mounted` is a lifecycle hook which we will explain later
  mounted() {
    // `this` refers to the component instance.
    console.log(this.count) // => 1

    // data can be mutated as well
    this.count = 2
  }
}
</script>

<style scoped>

</style>