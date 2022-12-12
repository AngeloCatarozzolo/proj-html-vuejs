<script>
export default {
  name: 'appMain6',
}
</script>

<template>
    <div class="container">
      <div class="card">  
        <div class="center">
          <h2>What Our client Say</h2>
        </div>
        <div class="center">  
          <img src="../assets/testimonials-2.jpg" alt="testimonial">
        </div>
        <div class="center">
          <p>Ability proceeds from a fusion of skills, knowledge, understanding and imagination, consolidated by experience</p>
        </div>
        <div class="center">
          <p>Luis Desalvo, CREO TECH</p>
        </div>
        <div class="center">
          <input type="radio"><input type="radio">
        </div>
      </div>
    </div>
</template>

<style lang="scss" scoped>
.container{
  .card{
    margin-top: 6.25rem;
    .center{
      display: flex;
      justify-content: center;

      input{
        margin-bottom: 6.25rem;
      }
    }
  }
}
</style>