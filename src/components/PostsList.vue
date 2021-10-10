<template>
  <h2>Post lists:</h2>
  <div class="postlists">
    <div v-for="post in posts" :key="post.id" class="">
      <SinglePost :post="post"/>
    </div>
  </div>
</template>

<script>
import SinglePost from './SinglePost.vue'
export default {
  props: ['posts'],
  components: { SinglePost },
  setup(props){
    
    
  }
}
</script>

<style>

</style>