<template>
  <div class="container">

    <TheNavbar/>
    <nuxt/>
    
  </div>
</template>

<script>
  import TheNavbar from '@/components/TheNavbar'

  export default {
    components: {
      TheNavbar
    }
  };

</script>


<style>
  .button--green {
    display: inline-block;
    border-radius: 4px;
    border: 1px solid #3b8070;
    color: #3b8070;
    text-decoration: none;
    padding: 10px 30px;
  }

  .button--green:hover {
    color: #fff;
    background-color: #3b8070;
  }

  .button--grey {
    display: inline-block;
    border-radius: 4px;

  }

</style>
