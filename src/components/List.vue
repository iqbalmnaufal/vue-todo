<template>
  <div style="margin-top: 20px;">
    <ul class="list-group">
      <li class="list-group-item" v-for="todo in todos" :key="todo">{{ todo }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    todos: {
      type: Array,
      default: []
    }
  }
}
</script>