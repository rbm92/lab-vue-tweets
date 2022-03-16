<template>
  <div>
    <img :src="src" className="profile" alt="profile" />
  </div>
</template>

<script>
export default {
  name: "ProfileImage",
  props: {
    src: String,
  },
};
</script>

<style>
</style>