<template>
  <div class="home">
    <h1>Home!</h1>
    <PostList :posts="posts"/>
  </div>
</template>

<script>
import {ref} from 'vue'
import PostList from '../components/PostsList.vue'
export default {
  name: 'Home',
  components: { PostList},
  setup(){
    const posts = ref([
      {title: 'Greeting', body: '  Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae doloremque adipisci animi laudantium nostrum tenetur alias. Beatae minima laudantium doloribus. Ex voluptatum earum totam soluta, illum, architecto similique alias laudantium iste officia consequatur aperiam exercitationem labore eum quo aspernatur mollitia beatae. Atque laudantium eius ad? Eaque facere repudiandae, vitae consectetur dolorum, ratione vel ad beatae id at quos consequuntur dicta molestias hic. Odit, placeat error delectus quia laudantium, ipsa omnis praesentium quisquam dolorem quas nesciunt aspernatur rem nobis a sunt ipsam laboriosam. Veniam ratione reprehenderit quidem expedita nam natus, maxime explicabo dolor sapiente. Culpa, tempora dignissimos facere perspiciatis illum eligendi distinctio reprehenderit laborum labore ipsum qui non suscipit minima nostrum libero quod dolorem maxime nisi nihil sequi quaerat? Cupiditate illo, non necessitatibus excepturi, doloribus nostrum dolore voluptate officia perferendis eaque quam sed. Cupiditate ex nesciunt, aliquid debitis esse itaque minima incidunt sapiente voluptas? Deleniti, amet. Harum quia placeat possimus aspernatur tenetur dolor repudiandae consequatur impedit autem. Corrupti, autem harum? At, ad aliquid nihil dolores libero eum esse facere quidem nam odit. Tempore labore libero accusantium tenetur consequatur, voluptatem optio, velit quo, ad impedit culpa. Odio beatae adipisci harum repellat doloremque enim a facere. Deleniti, perspiciatis quo explicabo dolor harum debitis.', id:1 },
      {title: 'A body', body: 'Hi this is my body!', id: 2}
    ]) 
    return { posts }
  }
}
</script>

<style>

</style>