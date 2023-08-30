<template>
<div :key="task.id" v-for="task in tasks">
  <Task: task="task"/>
</div>
    <Task/>
</template>

<script>
import Task from "@/components/Task.vue";

export default {
  name:'TasksComp',
  props:{
    tasks:Array
  },
  components:{
    Task
  }
}
</script>