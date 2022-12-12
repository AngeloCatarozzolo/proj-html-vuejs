<script>
export default {
  name: 'appMain7',
}
</script>

<template>
    <div class="container">
      <div class="center">
        <h2>Start Your Free Consultation</h2>
      </div>
      <div class="center">
        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium</p>
      </div>
      <div class="center">  
        <button class="orange">CONTACT US NOW</button>
      </div>
    </div>
</template>

<style lang="scss" scoped>
  .container{
    background-image: url(../assets/CTA-seo-1.jpg);
    height: 37.5rem;
    .center{
      display: flex;
      justify-content: center;
      .orange{
        color: white;
      background-color: #ffa837;
      width: 9.375rem;
      height: 2.5rem;
      border-radius: 10%;
      }
    }
  }
</style>