<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news!</h1>
    </section>
    <section class="featured-posts">
      <PostPreview 
        id='1'
        thumbnail= "https://cdn.techinasia.com/wp-content/uploads/2017/01/code-1839406_1280-750x500.jpg"
        title="Hello there!"
        previewText="This is my first post!"/>
      <PostPreview 
        id='1'
        thumbnail= "https://cdn.techinasia.com/wp-content/uploads/2017/01/code-1839406_1280-750x500.jpg"
        title="Hello there for the second time!"
        previewText="This is my Second post!"/>
      <PostPreview 
        id='1'
        thumbnail= "https://cdn.techinasia.com/wp-content/uploads/2017/01/code-1839406_1280-750x500.jpg"
        title="Hello there for the third time!"
        previewText="This is my Third post!"/>        
    </section>
  </div>
</template>


<script>
import PostPreview from '@/components/Posts/PostPreview'

export default{
  components: {
    PostPreview: PostPreview
  }
}
</script>


