<template>
    <div class="cen">
        <div class="recipes">
            <div class="recipes-up">
                <h2>POPULAR RECIPES</h2>
                <h4>
                    Aquilam erat voluptat. Ut quis ligula a magna blandit finibus.
                    Suspendisse maximus lacus non nunc lobortis
                </h4>
            </div>
            <div class="recipes-main">
                <div class="recipes-sx">
                    <img src="img/Yogurt-Nan-1200x790.jpg" alt="" />
                    <div class="recip-dw">
                        <h3>Lunch Favorite with Salad. Naan And Beans</h3>
                        <h4>Bakery, Featured, Healthy, Latest Recipes, Staff Picks</h4>
                        <hr />
                        <h4>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident
                            quo dolore nobis impedit. Natus deleniti a tenetur perspiciatis
                            asperiores corporis beatae nisi, deserunt voluptas eos voluptates
                            commodi porro omnis itaque?Lorem ipsum dolor sit amet consectetur
                            adipisicing elit. Provident quo dolore nobis impedit.
                        </h4>
                        <h4 class="learn">LEARN MORE</h4>
                    </div>
                </div>
                <div class="recipes-dx">
                    <div v-for="(recip, i) in foodimg" :key="i">
                        <img :src="'/img/' + recip" alt="" />
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            foodimg: [
                "Mixed-fruits.jpg",
                "r-rachel-park-366508-unsplash-min.jpg",
                "r-michelle-tsang-500721-unsplash-min.jpg",
                "quick-summer-drink-460x295.jpg",
                "r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg",
                "perfect-cosmopolitan-460x295.jpg",
                "fi2x-6-460x295.jpg",
                "r-brooke-lark-96398-unsplash-min-460x295.jpg",
            ],
        };
    },
};
</script>
  
<style scoped lang="scss">
@import "../style/recipes.scss";
</style>