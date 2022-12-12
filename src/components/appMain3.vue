<script>
export default {
  name: 'appMain3',
}
</script>

<template>
    <div class="container">
        <div class="h-main">
            <div class="center">
                <h2>Our Work</h2>
            </div>
            <div class="center">
                <p>Sed ut perspiciatis unde omni iste natus error sit voluptatem accusantium doloremque laudantium.</p>
            </div>
        </div>
        <div class="b-main">
            <div class="riga">
                <div class="card">
                    <img src="../assets/case-study-gallery-3-1-400x300.jpg" alt="">
                </div>
                <div class="card">
                    <img src="../assets/case-study-gallery-2-400x300.jpg" alt="">
                </div>
                <div class="card">    
                    <img src="../assets/case-study-gallery-1-1-400x300.jpg" alt="">
                </div>    
            </div>
            <div class="riga">
                <div class="card">
                    <img src="../assets/case-study-gallery-4-1-400x300.jpg" alt="">
                </div>    
                <div class="card">
                    <img src="../assets/case-study-gallery-5-1-400x300.jpg" alt="">
                </div>
                <div class="card">
                    <img src="../assets/case-study-gallery-6-1-400x300.jpg" alt="">
                </div>
            </div>
        </div>
        <button class="orange">VIEW OUR WORK</button>
    </div>
</template>

<style lang="scss" scoped>
    .container{
        
        .h-main{
            .center{
                display: flex;
                justify-content: center;
            }
        }
        .b-main{
            display: flex;
            justify-content: center;
            .riga{
                .card{
                    margin-left: .625rem;
                    img{
                        width: 250px;
                        height: 150px;
                    }
                }
            }
            
        }
    }
</style>