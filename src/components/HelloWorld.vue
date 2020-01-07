 <!-- ----------------------TEMPLATAE START--------------- -->

<template>
  <el-row :gutter="20">
    <el-col :span="12">
      <div class="grid-content bg-purple-dark">
        <div id="root">
          <h1 class="m-0">{{msg}}</h1>
        </div>
      </div>
    </el-col>
    <el-col :span="12">
      <div class="grid-content bg-purple-dark">
        <div id="root">
          <h1 class="m-0"><el-input v-model="msg"></el-input></h1>
        </div>
      </div>
    </el-col>
  </el-row>
</template>

<!-- ----------------------TEMPLATAE END--------------- -->

<!-- ----------------------SCRIPT START--------------- -->

<script>
export default {
  name: 'HelloWorld',
  data: ()=> {
    return {
      msg: 'This is my first Vue-app'
    }
  }
}
</script>

<!-- ----------------------SCRIPT END--------------- -->

<!-- ----------------------STYLE START--------------- -->

<style>
@import './../assets/style.css';
.bg-purple-dark {
    background: var(--purpleBg);
    border-radius: 5px;
  }
.m-0 {
  margin: 0px;
}
</style>

<!-- ----------------------STYLE END--------------- -->