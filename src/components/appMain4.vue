<script>
export default {
  name: 'appMain4',
}
</script>

<template>
    <div class="container">
        <div class="h-main">
            <div class="center">
                <h2>Our Plans</h2>
            </div>    
            <div class="center">    
                <p>Sed ut perspiciatis unde omnis iste naturs error sit voluptatem accusantium doloremque laudantium.</p>
            </div>
        </div>
        <div class="b-main">
            <div class="card">
                <h4>Standard</h4>
                <p class="price">$19.99 monthly</p>
                <p>5 Projects</p>
                <p>5 GB Storage</p>
                <p>Unlimited Users</p>
                <button class="orange">START TODAY</button>
            </div>
            <div class="card">
                <h4>Premium</h4>
                <p class="price">$29.99 monthly</p>
                <p>10 Projects</p>
                <p>15 GB Storage</p>
                <p>Unlimited Users</p>
                <button class="orange">START TODAY</button>
            </div>
            <div class="card">
                <h4>Professional</h4>
                <p class="price">$39.99 monthly</p>
                <p>15 Projects</p>
                <p>30 GB Storage</p>
                <p>Unlimited Users</p>
                <button class="orange">START TODAY</button>
            </div>
            <div class="card">
                <h4>Extreme</h4>
                <p class="price">$59.99 monthly</p>
                <p>Unlimited Projects</p>
                <p>Unlimited Storage</p>
                <p>Unlimited Users</p>
                <button class="orange">START TODAY</button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container{
    background-image: url(../assets/background1.jpg);
    height: 25rem;
    .h-main{
        .center{
            display: flex;
            justify-content: center;
        }
    }
    .b-main{
        margin-left: 31.25rem;
        margin-right: 31.25rem;
        display: flex;
        justify-content: space-between;;
        
        .card{
            background-color: white;
            width: 150px;
            button{
            border-radius: 10%;
                button:hover{
                    color: orange;
                   
                    position: absolute;
                    height: 5px;
                    width: 0;
                    left: 0;
                }
        }
    }
}
}
</style>