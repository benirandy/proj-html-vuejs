<template>
    <div>
        <div class="up-header">
            <div class="up-sx">
                <h6>Download App</h6>
                <h6 class="ios">iOS</h6>
                <h6>Advertise with us</h6>
            </div>
            <div class="up-dx">
                <i class="fab fa-facebook-f"></i>
                <i class="fab fa-instagram"></i>
                <i class="fab fa-twitter"></i>
                <i class="fab fa-youtube"></i>
            </div>
        </div>
        <div class="logo">
            <img src="img/avada-food-logo-2x.png" alt="logo" />
        </div>
        <div class="menu">
            <div v-for="(men, i) in menu" :key="i" class="main-men">
                <h3 class="men">{{ men }}</h3>
                <div class="linea"></div>
            </div>
            <i class="fas fa-search"></i>
        </div>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            menu: ["Home", "Recipes", "Places", "Blog", "About", "Contact"],
        };
    },
};
</script>
  
<style scoped lang="scss">
@import "../style/header.scss";
</style>