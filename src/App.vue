<template>
  <div>
    <h1>hi from vue.js craash course</h1>
    <Todofile />
  </div>
</template>

<script>
import Todofile from "./views/todolist.vue"
export default {
  name: "App",
  views: {
    Todofile
  }
};
</script>


<style>
body {
  background-color: #000;
  color: #bdb9b9;
}
</style>
