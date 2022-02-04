<template>
    <div class="admin-post-page">
        <section class="update-form">
            <AdminPostForm :post="loadedPost"/>
        </section>
    </div>
</template>

<script>
import AdminPostForm from '@/components/Admin/AdminPostForm'
export default {
    components:{
        AdminPostForm
    },
    data (){
        return{
            loadedPost: {
                author: 'Paula',
                title: 'My awesome post',
                content: 'Super amazing, thanks for that!',
            }
        }
    }
};
</script>