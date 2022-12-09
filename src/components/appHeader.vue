<script>
export default {
  name: 'appHeader',
}
</script>

<template>
  <div class="container">
    <div class="h-header">
      <div class="logo">
        <img src="../assets/logo_seo_w_1x.png" alt="logo">
      </div>
      <nav>
        <ul class="nav-link">
          <li><a href="#"> Home</a></li>
          <li><a href="#">Who We Are</a></li>
          <li><a href="#">What We Do</a></li>
          <li><a href="#">Where We Work</a></li>
          <li><a href="#">Careers <button>APPLY</button></a></li>
          <li><a href="#">News</a></li>
          <li><button>GET IN TOUCH NOW</button></li>
        </ul>
      </nav>
    </div>
    <div class="b-header">
      <h1>SEM Campaigns Made <br> Simple Aith Avada</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br> Phasellus eu ornare erat. Curabitur pulvinar elit.</p>
      <button class="b-orange">BUY AVADA NOW</button> <button class="b-blue">contact us</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  background-image: url(../assets/1-hero-image.png);
  background-repeat: no-repeat;
  background-size: cover;
  align-items: center;
  width: 100%;
  height: 800px;
  .b-orange{
    color: white;
    background-color: #ffa837;
    //border da fixare
    border-radius: 20%;
  }
  .b-blue{
    color: white;
    background-color: #0369d7;
    //border da fixare
    border-radius: 20%;
  }
  .h-header{
    display: flex;
    justify-content: space-between;
  }
  .b-header{
    margin-top: 9.375rem;
    margin-left: 31.25rem;
  }
  .logo{
      height: 100px;
      width: 62.5rem;
      float: right;
      display: flex;
      justify-content: center;
  }
  nav{
      justify-content: center;
      width: 100%;
      display: flex;
      align-items: center;
      .nav-link{
          display: flex;
          justify-content: space-between;
          li{
              list-style-type: none;
              margin-right: 1.875rem;
              text-transform: uppercase
            } 
            // transition
              a{
                position: relative;
                text-decoration: none;
                color: white;
                letter-spacing: .0313rem;
                padding: 0;
                }
                a:after{
                    content: "";
                    position: absolute;
                    height: 5px;
                    width: 0;
                    left: 0;
                }
                a:hover{
                    color: #ffa837;
                }
        }
    }
}
</style>
