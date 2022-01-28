<template>
    <div class="posts-page">
    <section class="post-list">
      <PostPreview 
        id='1'
        thumbnail= "https://cdn.techinasia.com/wp-content/uploads/2017/01/code-1839406_1280-750x500.jpg"
        title="HTML/CSS"
        previewText="Always wanted to know how to build your own website?"/>
      <PostPreview 
        id='2'
        thumbnail= "https://static.nieuwsblad.be/Assets/Images_Upload/2021/10/28/d6c7bc61-4380-4ecf-9dd1-a49a16ccef58.jpg"
        title="QR-code"
        previewText="QR-code the future?"/>
      <PostPreview 
        id='3'
        thumbnail= "https://i2-prod.manchestereveningnews.co.uk/incoming/article14379834.ece/ALTERNATES/s615/050318_LRR_MEN_WomenTech.jpg"
        title="Artificial intelligence"
        previewText="The real difference between a person and a robot"/>
      <PostPreview 
        id='4'
        thumbnail= "https://findstack.com/wp-content/uploads/2020/12/The-Ultimate-List-of-Internet-of-Things-Statistics.jpg"
        title="IoT"
        previewText="The internet of things"/>                  
    </section>
    </div>
</template>
<script>
import PostPreview from '@/components/Posts/PostPreview'

export default{
    components: {
        PostPreview
    }
}
</script>

<style scoped>
.post-page{
    display: flex;
    justify-content: center;
    align-items: center;
}

.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
} 
</style>
