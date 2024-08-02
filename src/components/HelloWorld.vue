<template>
  <v-container class="fill-height">
    <v-card title="Use tab to focus items" class="mx-auto" max-width="300">
      <v-list :items="items" rounded nav />
    </v-card>
  </v-container>
</template>

<script setup>
  const items = [
    {
      title: 'Item #1',
      value: 1,
    },
    {
      title: 'Item #2',
      value: 2,
    },
    {
      title: 'Item #3',
      value: 3,
    },
  ]
</script>
