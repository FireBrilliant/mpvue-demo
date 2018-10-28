<template>
<div>
  <h1>vuejs is good</h1>
  <todolist></todolist>
</div>
</template>

<script>
  import Todolist from '@/components/Todolist'
  export default {
    name: 'index',
    components: {
      Todolist
    }
  }
</script>

<style scoped>
h1{
  color:red;
}
</style>
