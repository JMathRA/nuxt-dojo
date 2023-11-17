<template>
  <div>
    <p>Products details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate quaerat
      fugit porro, facere cumque temporibus unde totam magnam id quasi assumenda
      esse quas et iste voluptatum? Perspiciatis voluptates quae saepe?
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;

definePageMeta({
    layout: 'products'
  })
</script>

<style scoped></style>
