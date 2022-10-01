<template>
  <div>
    <TheNavBar/>
    <nuxt/>
  </div>
</template>


<script>
import TheNavBar from '@/components/TheNavBar'

export default {
  components: {
    TheNavBar
  }
}
</script>

<style>
  .button-green {
    display: inline-block;
    border-radius: 4px;
    border: 1px solid #3b8070;
    color: #3b8070;
    text-decoration: none;
    padding: 10px 30px;
  }

  .button-green:hover {
    color: #fff;
    background-color: #3b8070;
  }
</style>
