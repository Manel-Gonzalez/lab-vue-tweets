<template>
  <div className="profile">
    <img :src="url" className="profile" alt="profile"/>
  </div>
</template>

<script>
export default {
    props:{
        url:String
    }
}
</script>

<style>

</style>