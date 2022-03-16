<template>
  <div>
    <span className="timestamp">{{ timestamp }}</span>
  </div>
</template>

<script>
export default {
  name: "Timestamp",
  props: {
    timestamp: String,
  },
};
</script>

<style>
</style>