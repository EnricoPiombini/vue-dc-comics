<template>
    <div>
        <div class="bg-image">
            <div class="row justify-content-around">
                <div class="col-5">
                    <div class="row g-3">
                        <div class="content d-flex p-5 m-2">
                            <div class="col-4">
                                <div class="content text-start">
                                    <h5 class="text-white fw-bold ">DC COMICS</h5>
                                    <ul class="list-unstyled">
                                        <li>Characters</li>
                                        <li>Comics</li>
                                        <li>Movies</li>
                                        <li>TV</li>
                                        <li>Games</li>
                                        <li>Videos</li>
                                        <li>News</li>
                                        <h5 class="text-white fw-bold mt-3">SHOP</h5>
                                        <li>Shop DC</li>
                                        <li>Shop DC Collectibles</li>

                                    </ul>
                                </div>
                            </div>
                            <div class="col-4">
                                <div class="content text-start">
                                    <h5 class="text-white fw-bold">DC</h5>
                                    <ul class="list-unstyled">
                                        <li>Terms of Use</li>
                                        <li>Privacy Policy(New)</li>
                                        <li>Ad Choices</li>
                                        <li>Advertising</li>
                                        <li>Jobs</li>
                                        <li>Subscriptions</li>
                                        <li>Talent Workshops</li>
                                        <li>CPSC Certificates</li>
                                        <li>Ratings</li>
                                        <li>Shop Help</li>
                                        <li>Contact Us</li>
                                    </ul>
                                </div>
                            </div>

                            <div class="col-4">
                                <div class="content text-start">
                                    <h5 class="text-white fw-bold">SITES</h5>
                                    <ul class="list-unstyled">
                                        <li>DC</li>
                                        <li>MAD Magazine</li>
                                        <li>DC Kids</li>
                                        <li>DC Universe</li>
                                        <li>DC Power Visa</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-6">
                    <div class="bg-logo">

                    </div>


                </div>

            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: "TheFooter",
}
</script>

<style scoped>
.bg-image {
    background-image: url("/public/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
}

.bg-logo {
    background-image: url("/public/img/dc-logo-bg.png");
    min-height: 460px;
    background-repeat: no-repeat;
    background-position: center;
}

ul {
    list-style: none;
    margin-bottom: 0;
    margin-left: 0;
    margin-right: 0;
    margin-top: 10px;
    padding: 0;
}

li {
    color: #959595;
    font-size: 14px;
    margin: 3px;
}

ul li a {
    color: lightslategray;
}
</style>