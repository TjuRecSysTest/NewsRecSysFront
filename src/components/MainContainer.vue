<template>
  <div class="container">
    <el-row>
      <el-col :span="8">

      </el-col>
      <el-col :span="8">
        <div>2</div>
      </el-col>
      <el-col :span="8">
        <div>3</div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
let userData = require("../assets/user.json")

export default {
  name: "MainContainer",
  data(){
    return {
      userList:userData
    }
  }
}
</script>

<style scoped>
.container {
  width: 1140px;
  margin: 0 auto;
}
</style>