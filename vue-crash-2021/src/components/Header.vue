<template>
  <header>
    <h1>{{ title }}</h1>
    <Button text="Add Task" color="green"/>
  </header>
</template>
<script>
import Button from "@/components/Button.vue";
export default {
  name: 'HeaderItem',
  props:{
    title:String,
  },
  components:{
    Button
  }
}
</script>
<style>
  header{
  display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
  }
</style>