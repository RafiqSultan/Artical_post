<template>
  <div class="container">
    <h1>{{ pageName }}</h1>
    <p>{{ PageDescription }}</p>
    <div class="row">
      <div class="col-md-5">
        <div class="posts-area">
          <blog-post />
        </div>
      </div>
      <div class="col-md-4">
        <div class="sidbar">
          <blog-sidebar />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import BlogSidebar from "@/components/Blogs/BlogSidebar.vue";
import BlogPost from "@/components/Blogs/BlogPost.vue";
export default {
  data: function () {
    return {
      pageName: "Blog",
      PageDescription: "This is blogs",
    };
  },
  name: "blogPage",
  components: {
    BlogSidebar,
    BlogPost,
  },
};
</script>
