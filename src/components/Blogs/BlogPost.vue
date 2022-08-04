<template>
  <div class="post-box">
    <span class="post-views">10</span>
    <h3 class="post-title">Post Title</h3>
    <span class="post-date">3-8-2022</span>
    <p class="post-content">
      Lorem ipsum, dolor sit amet consectetur adipisicing elitconsectetur
      adipisicing elit. Perspiciatis, rem.
    </p>

    <div class="row">
      <div class="col-sm-6">
        <span class="post-author">post Auther</span>
      </div>
      <div class="col-sm-6 text-right">
        <span class="post-category">post Category</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "blogPost",
};
</script>

<style lang="scss" scoped>
.post-box {
  padding: 15px;
  background-color: #fff;
  box-shadow: 0 0 10px #ddd;
  position: relative;
  text-align: left;
  .post-views {
    position: absolute;
    right: 0;
    top: 0;
    background-color: rgb(48, 160, 44);
    border-radius: 5px;
    padding: 1px 5px;
    color: #fff;
    text-align: center;
    font-weight: bold;
  }
  .post-date {
    display: block;
    padding: 0 0 5px;
    color: #888;
    font-size: 13px;
  }
  .post-content {
    line-height: 1.7;
    color: #666;
  }
  .post-author {
    background-color: #333;
    color: #fff;
    border-radius: 5px;
    padding: 5px 10px;
  }
  .post-category {
    background-color: rgb(136, 16, 36);
    color: #fff;
    border-radius: 5px;
    padding: 5px 10px;
  }
}
</style>
