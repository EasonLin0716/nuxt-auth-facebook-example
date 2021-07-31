<template>
  <div>請稍候...</div>
</template>

<script>
export default {
  name: "AuthFacebookCallback",
  async mounted() {
    const { code } = this.$route.query;
    const { data } = await this.$axios.post(
      `${location.origin}/facebook/login?code=${code}`
    );
    console.log(data);
  }
};
</script>
