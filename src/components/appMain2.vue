<script>
export default {
  name: 'appMain2',
}
</script>

<template>
    <div class="container">
        <div class="h-main">
            <h2>See Our Top Notch Services</h2>
            <p>Sed ut perspiciatis unde omnis iste natus error sit volupatatem <br> accusantium doloremque laudantium</p>
        </div>
        <div class="b-main">
            <div class="card">
                <font-awesome-icon class="orange" icon="fa-brands fa-google" />
                <h4>Google SEO</h4>
                <p>Vestibulum in lacinia metus. Suspandisse in enim ipsum. Nulla facillisi. Donec ante turpis, dictum sed magna et, dapibus faucibus odio.</p>
                <p class="orange">Read More ></p>
            </div>
            <div class="card">
                <font-awesome-icon class="orange" icon="fa-solid fa-gear" />
                <h4>Brand Strategy</h4>
                <p>Vestibulum in lacinia metus. Suspandisse in enim ipsum. Nulla facillisi. Donec ante turpis, dictum sed magna et, dapibus faucibus odio.</p>
                <p class="orange">Read More ></p>
            </div>
            <div class="card">
                <font-awesome-icon class="orange" icon="fa-solid fa-building" />
                <h4>Local SEO</h4>
                <p>Vestibulum in lacinia metus. Suspandisse in enim ipsum. Nulla facillisi. Donec ante turpis, dictum sed magna et, dapibus faucibus odio.</p>
                <p class="orange">Read More ></p>
            </div>
            <div class="card">
                <font-awesome-icon class="orange" icon="fa-solid fa-chart-column" />
                <h4>Local Analysis</h4>
                <p>Vestibulum in lacinia metus. Suspandisse in enim ipsum. Nulla facillisi. Donec ante turpis, dictum sed magna et, dapibus faucibus odio.</p>
                <p class="orange">Read More ></p>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container{
    background-image: url(../assets/pattern_background.png);
    width: 100%;
    height: 100%;
    background-color: blue;

    .h-main{
        display: flex;
        justify-content: center;
    }
    .b-main{
        display: flex;
        justify-content: space-between;
        .card{
            width: 12.5rem;
            background-color: aqua;
            .orange{
                color: orange;
            }
        }
    }
}
</style>