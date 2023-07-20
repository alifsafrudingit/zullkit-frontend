<script setup>
import { ref } from 'vue'
import NewItemsCard from '../NewItemsCard.vue'

const items = ref([
  {id: 1, title: 'Mobile UI Kit', image: 'items-1.jpg', group_kit: 'Mobile UI Kit'},
  {id: 2, title: 'Online Doctor Consultation', image: 'items-2.jpg', group_kit: 'Website UI Kit'},
  {id: 3, title: 'Banking Crypto', image: 'items-3.jpg', group_kit: 'Mobile UI Kit'},
])
</script>

<template>
  <div class="container px-4 mx-auto my-16 md:px-12">
      <h2 class="mb-4 text-xl font-medium md:mb-0 md:text-lg">New Items</h2>
      <div class="flex flex-wrap -mx-1 lg:-mx-4">
        <NewItemsCard 
          v-for="item in items"
          :id="item.id"
          :title="item.title"
          :image="item.image"
          :group_kit="item.group_kit"
        />
      </div>
    </div>
</template>