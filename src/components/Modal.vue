<template>
  <div>
    <button @click="$emit('close-modal')" />
    <slot />
  </div>
</template>

<script>
export default {
  // props: ['onClose']
}
</script>
