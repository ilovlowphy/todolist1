<template>
  <form action="">
    <input type="text"> <input type="submit" value="Submit" class="btn">
  </form>
</template>

<script>
export default {

}
</script>

<style scoped>
form {
  display: flex;
}
input[type="text"] {
  flex: 10;
}
input[type='submit'] {
  flex: 2;
}
</style>