<template>
    <div class="container">
        <nav class="mnav d-flex justify-content-around align-items-center p-4">
            <div class="left-side">
                <a class="navbar-brand" href="#">
                    <img src="img/dc-logo.png" class="d-inline-block align-text-top">
                </a>
            </div>
            <div class="right-side">
                <ul class="d-flex list-unstyled">
                    <li v-for="(link, i) in navLinks" :key="i">
                    <a class="navbar-brand" :href="link.href"> {{link.name}} </a></li>

                    <!-- <li><a class="navbar-brand" href="#">COMICS</a></li>
                    <li><a class="navbar-brand" href="#">MOVIES</a></li>
                    <li><a class="navbar-brand" href="#">TV</a></li>
                    <li><a class="navbar-brand" href="#">GAMES</a></li>
                    <li><a class="navbar-brand" href="#">COLLECTIBLES</a></li>
                    <li><a class="navbar-brand" href="#">VIDEOS</a></li>
                    <li><a class="navbar-brand" href="#">FANS</a></li>
                    <li><a class="navbar-brand" href="#">NEWS</a></li>
                    <li><a class="navbar-brand" href="#">SHOP</a></li> -->
                </ul>
            </div>
        </nav>
    </div>
</template>


<script>
export default {
    name: "TheNavbar",
    data() {
        return {
            navLinks: [
                {
                    name: "CHARACTERS",
                    href: "#"
                },
                {
                    name: "COMICS",
                    href: "#"
                },
                {
                    name: "MOVIES",
                    href: "#"
                },
                {
                    name: "TV",
                    href: "#"
                },
 {
                    name: "GAMES",
                    href: "#"
                },
                 {
                    name: "COLLECTIBLES",
                    href: "#"
                },
                 {
                    name: "VIDEOS",
                    href: "#"
                },
                 {
                    name: "FANS",
                    href: "#"
                },
                 {
                    name: "NEWS",
                    href: "#"
                },
                 {
                    name: "SHOP",
                    href: "#"
                }

            ]
        }
    }
}
</script>

<style scoped>
ul li a {
    margin: 1rem;
    font-size: 15px;
}
</style>