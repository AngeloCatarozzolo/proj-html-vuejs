<script>
export default {
  name: 'appFooter',

  props:{
    txt: String,
    },
   created() {
    this.txt = 'Home'
    }
}
</script>

<template>
<div class="container">
  <div class="logo">
    <img src="../assets/logo_seo_1x.png" alt="logo">
  </div>
  <nav>
    <ul class="nav-link">
      <li><a href="#"> {{txt}}</a></li>
      <li><a href="#">Who We Are</a></li>
      <li><a href="#">What We Do</a></li>
      <li><a href="#">Where We Work</a></li>
      <li><a href="#">Careers</a></li>
      <li><a href="#">News</a></li>
    </ul>
  </nav>
  <div class="copiright">
    <p>copiright 2012-2020 | AvadaTheme by ThemeFusion | All Right Reserved | Powered by WordPress</p>
  </div>
  <div class="social">
    <font-awesome-icon icon="fa-brands fa-facebook-f" />
    <font-awesome-icon icon="fa-brands fa-instagram" />
    <font-awesome-icon icon="fa-brands fa-twitter" />
    <font-awesome-icon icon="fa-brands fa-twitter" />
  </div>
</div>
</template>

<style lang="scss" scoped>
.container{
  .logo{
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
    .copiright{
      display: flex;
      justify-content: center;
    }
}
</style>
