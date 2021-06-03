<template> 
    <div class="carousel">

        <transition-group name="fade" tag="div">
            <div v-for="i in [currentIndex]" :key="i">
                <img :src="currentImg" />
            </div>
        </transition-group>

        <a class="prev" @click="prev" href="#">&#10094;</a>
        <a class="next" @click="next" href="#">&#10095;</a>
    
    </div>
</template>

<script>
        export default {
            name: "Slider",
            data() {
                return {
                images: [
                    require("../assets/blade/Blade-3060-4-ELM-BLK+Sides.jpg"),
                    require("../assets/blade/Blade-3060-4-WHT-WHT+Sides.jpg"),
                    require("../assets/blade/Blade-3060-6-MPL-WHT+Sides.jpg")
                ],
                timer: null,
                currentIndex: 0
                };
            },

            // mounted: function() {
            //     this.startSlide();
            // },

            methods: {
                // startSlide: function() {
                // this.timer = setInterval(this.next, 4000);
                // },

                next: function() {
                this.currentIndex += 1;
                },
                prev: function() {
                this.currentIndex -= 1;
                }
            },

            computed: {
                currentImg: function() {
                return this.images[Math.abs(this.currentIndex) % this.images.length];
                }
            }
    };
</script>

<style scoped>
    @import '../styles/slider.css';
</style>
