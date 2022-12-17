<template>
    <div class="blog-preview-layout">
      <img src="../assets/mug.jpg" alt="" class="image-size" />
      <div class="blog-preview">
        <h2>How to customize your coffee mug</h2>
        <h5>By Olivia</h5>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt
        </p>
      </div>
      <img src="../assets/mug.jpg" alt="" class="image-size" />
      <div className="blog-preview">
        <h2>Where to buy good coffee</h2>
        <h5>By Popeye</h5>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt
        </p>
      </div>
      <img src="../assets/mug.jpg" alt="" class="image-size" />
      <div className="blog-preview">
        <h2>Do you know...</h2>
        <h5>By Lou</h5>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt
        </p>
      </div>
    </div>
</template>

<style scoped>
/* .content {
  max-width: 75%;
  margin: 40px auto;
  padding: 20px;
} */
.blog-preview-layout {
  display: grid;
  grid-template-columns: 1fr 2fr;
  column-gap: 5px;
}
.blog-preview {
  padding: 10px 16px;
  margin: 20px 0;
  border-bottom: 1px solid #fafafa;
}
.blog-preview:hover {
  box-shadow: 1px 3px 5px rgba(0, 0, 0, 0.1);
}
.blog-preview h2 {
  font-size: 20px;
  color: #6F42C1;
  margin-bottom: 8px;
}
.blog-preview h5 {
  color: #75d0c1;
}
.image-size {
  width: 200px;
  padding: 5%;
}
</style>