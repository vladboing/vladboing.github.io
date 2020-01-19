<template>
    <div class="container-fluid" style="background-color: #7f7f7f; color: white; height: 100vh; transform: skewY(-4deg); transform-origin: top left;">
        <div class="row" style="transform: skewY(4deg);">
            <div class="col-12">
                <div class="row" style="margin-top: 20vh;">
                    <div class="col-12 text-center">
                        <ul style="list-style: none; display: inline-flex;" class="m-auto">
                            <li style="margin: auto 400% auto -400%; text-transform: uppercase; font-weight: bold;">Work</li>
                            <li><a href=""><img src="../assets/icon.png" style="width: 100px; filter: drop-shadow(3px 3px 5px #616161);" alt="logo"></a></li>
                            <li style="margin: auto 0 auto 400%; text-transform: uppercase; font-weight: bold;">Me</li>
                        </ul>
                    </div>
                </div>
                <div class="row m-5">
                    <div class="col-12 text-center">
                        <h1 style="font-weight: bold; margin: 4rem 0 10px 0;letter-spacing: 7px; line-height: 110px; font-size: 5rem;">Vladyslav <br> Zdrachuk</h1>
                        <h3 style="font-weight: lighter;">PHP Developer</h3>
                        <h3 style="font-weight: lighter;">Magento 2 Backend Developer</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>
