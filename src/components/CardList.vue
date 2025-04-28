<script setup>
import Card from './Card.vue'

defineProps({
  items: Array,
})
const onClickAdd = () => {
  alert('Добавить!')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5"></div>
</template>
