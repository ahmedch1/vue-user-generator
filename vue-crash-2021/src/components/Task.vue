<template>
  <h3>{{task.text}}</h3>

</template>

<script>
export default {
  name: 'TaskItem',
  props:{
    task:Object
  }
}
</script>