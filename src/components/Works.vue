<template>
    <div class="container-fluid text-center" id="works">
        <div class="row">
            <div class="col-12">
                <h2>My Works</h2>
                <div class="container">
                    <div class="row">
                        <div class="col-12 col-md-6 col-sm-12 col-lg-6">
                            <div class="card">
                                <a href="https://fight4car.com/">
                                    <img class="card-img-top" src="@/assets/cars.png" alt="Card image cap">
                                </a>
                                <div class="card-body">
                                    <h5 class="card-title"><a href="https://fight4car.com/">Fight 4 Car</a></h5>
                                    <p class="card-text">Here you can buy used/new cars from Canada to Ukraine. Created
                                    using wordpress CMS.</p>
                                    <span id="tags">My work:</span>
                                    <span class="badge badge-info">Filters</span>
                                    <span class="badge badge-info">CSV Importing cars</span>
                                    <span class="badge badge-info">Fetching images collection from links</span>
                                    <span class="badge badge-info">Frontend adaptation</span>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-md-6 col-sm-12 col-lg-6">
                            <div class="card">
                                <a href="https://taxigarantsv.com.ua/">
                                    <img class="card-img-top" src="@/assets/taxi.png" alt="Card image cap">
                                </a>
                                <div class="card-body">
                                    <h5 class="card-title"><a href="https://taxigarantsv.com.ua/">Taxi Service</a></h5>
                                    <p class="card-text">Website for Taxi service. Created with Laravel 6, Vue and Bootstrap.</p>
                                    <span id="tags">My work:</span>
                                    <span class="badge badge-info">LiqPay integration</span>
                                    <span class="badge badge-info">Backend</span>
                                    <span class="badge badge-info">Frontend</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Works"
    }
</script>

<style scoped>

</style>