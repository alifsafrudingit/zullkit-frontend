<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div>
    <div class="p-8 border rounded-3xl">
      <h1 class="text-5xl font-semibold">
        $ 20 <span class="text-xl font-light text-gray-500">/month</span>
      </h1>
      <h2 class="text-lg font-semibold mt-7">Basic Plan</h2>
      <p class="mb-6 text-gray-500">Suitable for new team</p>
      <ul class="mb-6 text-gray-700">
        <li class="mb-3">
          <img src="@/assets/img/icon-check.png" class="float-left w-6 mr-2" alt="" />
          Customizable layers
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-check.png" class="float-left w-6 mr-2" alt="" />
          Official documentation
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-check.png" class="float-left w-6 mr-2" alt="" />
          SVG icons
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-check.png" class="float-left w-6 mr-2" alt="" />
          SVG illustrations
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-check.png" class="float-left w-6 mr-2" alt="" />
          Pre-built design screen
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-cross.png" class="float-left w-6 mr-2" alt="" />
          Coded template
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-cross.png" class="float-left w-6 mr-2" alt="" />
          Support 24/7
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-cross.png" class="float-left w-6 mr-2" alt="" />
          Private designer group
        </li>
        <li class="mb-3">
          <img src="@/assets/img/icon-cross.png" class="float-left w-6 mr-2" alt="" />
          Unlock cloning app
        </li>
      </ul>
      <RouterLink
        to="/success-payment"
        class="inline-flex items-center justify-center w-full px-8 py-3 text-base font-medium text-black bg-gray-200 border border-transparent rounded-full hover:bg-gray-300 md:py-2 md:text-md md:px-10 hover:shadow"
      >
        Checkout Now
      </RouterLink>
    </div>
  </div>
</template>
