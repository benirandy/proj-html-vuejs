<template>
    <div class="footers">
        <div class="f-imgs">
            <img src="/img/Yogurt-Nan.jpg" alt="" />
            <img src="/img/Mixed-fruits.jpg" alt="" />
            <img src="/img/r-rachel-park-366508-unsplash-min.jpg" alt="" />
            <img src="/img/r-michelle-tsang-500721-unsplash-min.jpg" alt="" />
        </div>
        <div class="footer">
            <div class="sx">
                <img src="/img/avada-food-logo-mob-2x.png" alt="" />
                <div class="icon">
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-instagram"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-youtube"></i>
                </div>
            </div>
            <div class="sx-c">
                <div v-for="(men, i) in footmen" :key="i">
                    {{ men }}
                </div>
            </div>
            <div class="dx-c">
                <h3>CONTACT</h3>
                <h4>775 New York Ave, brooklin,Kings,New York 11203</h4>
                <h4>+1000-505-0000</h4>
                <h4>info@your-domain.com</h4>
            </div>
            <div class="dx">
                <h3>GET OUR APP!</h3>
                <img src="/img/download-android.png" alt="" />
                <img src="/img/download-android.png" alt="" />
            </div>
        </div>
    </div>
</template>
  

<script>

export default {
    data() {
        return {
            footmen: ["Recipes", "Places", "Blog", "About", "Contact"],
        };
    },
};
</script>
  
<style scoped lang="scss">
@import "../style/footer.scss";
</style>