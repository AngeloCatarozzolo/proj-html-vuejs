<script>
export default {
  name: 'appMain5',
}
</script>

<template>
    <div class="container">
        <div class="h-main">
            <h2>Our News</h2>
            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium</p>
        </div>
        <div class="b-main">
            <div class="card">
                <img src="../assets/related-service-2-320x202.jpg" alt="">
                <h3 class="orange">Why You Need A SEO Agency Now</h3>
                <small>November 1st, 2017</small>
                <p>ALorem ipsum dolor sit amet, consecutor adipiscing elit. in et scelerisque sem. Nunc molesstie neque augue, at gravidia mi blandit</p>
            </div>
            <div class="card">
                <img src="../assets/related-service-4-320x202.jpg" alt="">
                <h3 class="orange">Why You Need A SEO Agency Now</h3>
                <small>November 1st, 2017</small>
                <p>ALorem ipsum dolor sit amet, consecutor adipiscing elit. in et scelerisque sem. Nunc molesstie neque augue, at gravidia mi blandit</p>
            </div>
            <div class="card">
                <img src="../assets/blog-post-6-320x202.jpg" alt="">
                <h3 class="orange">Why You Need A SEO Agency Now</h3>
                <small>November 1st, 2017</small>
                <p>ALorem ipsum dolor sit amet, consecutor adipiscing elit. in et scelerisque sem. Nunc molesstie neque augue, at gravidia mi blandit</p>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container{
    .b-main{    
        display: flex;
        justify-content: space-between;
        .card{
            width: 18.75rem;
        }
    }
}
</style>