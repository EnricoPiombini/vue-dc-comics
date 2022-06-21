<template>
    <div>
        <div class="d-flex gap-5 justify-content-center bg-primary p-4">
            <div class="d-flex align-items-center" v-for="(link, i) in bannerLinks" :key="i">
                <img :src= "link.img"  alt="" srcset="" class="w-40">
                <h6 class="text-white"> {{link.title}} </h6>
            </div>
            <!-- <div class="d-flex align-items-center">
                <img src="img/buy-comics-merchandise.png" alt="" srcset="" class="w-40">
                <h6>DC MERCHANDISE</h6>
            </div>
            <div class="d-flex align-items-center">
                <img src="img/buy-comics-shop-locator.png" alt="" srcset="" class="w-40">
                <h6>SUBSCRIPTION</h6>
            </div>
            <div class="d-flex align-items-center">
                <img src="img/buy-comics-subscriptions.png" alt="" srcset="" class="w-40">
                <h6>COMIC SHOP LOCATOR</h6>
            </div>
            <div class="d-flex align-items-center">
                <img src="img/buy-dc-power-visa.svg" alt="" srcset="" class="w-40">
                <h6>DC POWER VISA</h6>
            </div> -->
        </div>

    </div>
</template>


<script>
export default {
    name: "TheBannerBlue",
    data() {
        return {
            bannerLinks: [
                {
                    img: "img/buy-comics-digital-comics.png",
                    title: "DIGITAL COMICS"
                },
                {
                    img: "img/buy-comics-merchandise.png",
                    title: "DC MERCHANDISE"
                },
                {
                    img: "img/buy-comics-shop-locator.png",
                    title: "COMIC SHOP LOCATOR"
                },
                {
                    img: "img/buy-comics-subscriptions.png",
                    title: "SUBSCRIPTION"
                },
                {
                    img: "img/buy-dc-power-visa.svg",
                    title: "DC POWER VISA"
                },
            ]
        }
    }

}
</script>

<style>
.w-40 {
    width: 40px;
}
</style>