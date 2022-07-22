<template>
  <div>
    <Post />
  </div>
</template>

<script>
import Post from './Post.vue'; //경로 주의

export default {
    name: 'Container',
    components:{
        Post: Post,
    }
};
</script>

<style>
</style>