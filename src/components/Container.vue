<template>
  <div>
    <Post :data="data[0]" />
  </div>
</template>

<script>
import Post from './Post.vue'; //경로 주의

export default {
    name: 'Container',
    components:{
        Post: Post,
    },
    props:{
      data: Array,
    }
};
</script>

<style>
</style>