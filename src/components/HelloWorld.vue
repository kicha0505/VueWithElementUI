 <!-- ----------------------TEMPLATAE START--------------- -->

<template>
  <el-row>
    <el-col :span="24">
      <div class="grid-content bg-purple-dark">
        <div id="root">
          <h1>{{msg}}</h1>
        </div>
      </div>
    </el-col>
  </el-row>
</template>

<!-- ----------------------TEMPLATAE END--------------- -->

<!-- ----------------------SCRIPT START--------------- -->

<script>
// IMPORTS //
import Vue from "vue";

// DECLERATIONS //
new Vue({
  el: "#root",
  data: {
    msg: "This is my First app"
  }
});
</script>

<!-- ----------------------SCRIPT END--------------- -->

<!-- ----------------------STYLE START--------------- -->

<style>
.ulClass {
  list-style: none;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.el-button,
li {
  font-size: 20px !important;
}
.el-dialog__title {
  font-size: 30px !important;
  border-bottom: 2px solid #303133;
}
</style>

<!-- ----------------------STYLE END--------------- -->