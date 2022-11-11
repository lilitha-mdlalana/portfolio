<script setup>
defineProps({
  projectName: String,
  imagePath: String,
  prjectStack: String,
  projectDescription: String,
  projectStack: String,
  liveLink: String,
  githubLink: String,
});
</script>
<template>
  <div
    class="block overflow-hidden rounded-lg border border-gray-100 shadow-sm"
  >
    <img alt="Office" :src="imagePath" class="h-56 w-full object-cover" />

    <div class="p-6">
      <h5 class="text-xl font-bold font-poppins">
        {{ projectName }}
      </h5>
      <p class="mt-2 text-md text-gray-500 font-lato">
        <span class="font-bold font-poppins">STACK:</span> {{ projectStack }}
      </p>
      <p class="mt-2 text-md text-gray-500">
        <span class="font-bold font-poppins">DESCRIPTION:</span>{{ projectDescription }}
      </p>

      <a
        :href="githubLink"
        class="mt-4 inline-block border-b border-blue-500 pb-1 font-medium hover:text-blue-600 mr-6"
      >
        Github
        <span aria-hidden="true">&rarr;</span>
      </a>
      <a
        :href="liveLink"
        class="mt-4 inline-block border-b border-blue-500 pb-1 font-medium hover:text-blue-600"
      >
        Live Site
        <span aria-hidden="true">&rarr;</span>
      </a>
    </div>
  </div>
</template>
