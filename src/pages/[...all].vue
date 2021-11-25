<script setup lang="ts">
const { push } = useRouter()
const handleBack = () => push({ path: '/' })

</script>

<template>
  <div>
    <div>Not Found</div>

    <button
      class="btn"
      @click="handleBack"
    >
      Back
    </button>
  </div>
</template>
