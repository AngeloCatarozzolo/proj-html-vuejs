<script>
export default {
  name: 'appMain1',
}
</script>

<template>
  <div class="container">
    <div class="h-main">
      <div class="center">
        <h2><strong>Meet The New Agency SEO Template <br> From The Avada Team</strong></h2>
      </div>
      <div class="center">
        <p>Sed ut perspiciatis unde omnis iste natus error sit volupatatem <br> accusantium doloremque laudantium</p>
      </div>
    </div>
    <div class="b-main">
      <div class="card">
        <font-awesome-icon icon="fa-solid fa-road" />
        <h3>Establish Goal</h3>
        <p>aliquam non elit lacus. Praesent aliquet, <br> ipsum id scelerisque convallis, mi ligula <br> euismod odio, vel dictum mi risus a mi.</p>
      </div>
      <div class="card">
        <font-awesome-icon icon="fa-sharp fa-solid fa-video" />
        <h3>Work With a Team</h3>
        <p>Cras semper auctor aliquam. Sed porta sed <br> lacus sit amet consectetur. Lorem ipsum <br> dolor sit amet, consectetur adipiscin</p>
      </div>
      <div class="card">
        <font-awesome-icon icon="fa-solid fa-droplet" />
        <h3>Get Results</h3>
        <p>Vestibulum scelerisque egestas lectus sit <br> amet molestie. Donec consectetur cursus <br> est sed blandit. Nunc sed risus lacus.</p>
      </div>
    </div>
    <div class="f-main">
      <img src="../assets/agency-seo-desk-front-800x380.jpg" alt="">
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container{
  margin-left: 31.25rem;
  margin-right: 31.25rem;
  align-items: center;
  .h-main{
    .center{
      display: flex;
      justify-content: center;
    }
  
  }
  .b-main{
    display: flex;
    justify-content: space-between;
    .card{
      p{
        color: gray;
      }
    }
    

  }
  .f-main{
    display: flex;
    justify-content: center;
  }

}
</style>
