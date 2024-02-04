<template lang="">
    <footer class="bg-body-tertiary">
        <div class="container py-4 py-md-5 px-4 px-md-3 text-body-secondary">
            <div class="row">
                <div class="col-lg-3 mb-3">
                    <a class="d-inline-flex align-items-center mb-2 text-body-emphasis text-decoration-none" aria-label="Bootstrap">
                        <img src="https://cdn-thumbs.imagevenue.com/f7/b4/d5/ME17IVRQ_t.png" alt="twelve_Two_logo" id="logo">
                        <span class="fs-5 text-black border-bottom">Template Co.</span>
                    </a>
                    <ul class="list-unstyled small">
                        <li class="mb-2 text-black">Lorem ipsum dolor sit amet, consectetur adipiscing elit.Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
                        <li class="mb-2 text-black">licensed MIT, docs CC BY Temp~Co.</li>
                        <li class="mb-2 text-black">Lorem v5.3.2.</li>
                    </ul>
                </div>

                <div class="col-6 col-lg-2 offset-lg-1 mb-3">
                    <h5 class="text-black">Links</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2">Home</li>
                        <li class="mb-2">Docs</li>
                        <li class="mb-2">Examples</li>
                        <li class="mb-2">Icons</li>
                        <li class="mb-2">Themes</li>
                        <!-- <li class="mb-2">Blog</li>
                        <li class="mb-2">Swag Store</li> -->
                    </ul>
                </div>

                <div class="col-6 col-lg-2 mb-3">
                    <h5 class="text-black">Guides</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2">Getting started</li>
                        <li class="mb-2">Starter template</li>
                        <li class="mb-2">Webpack</li>
                        <li class="mb-2">Parcel</li>
                        <li class="mb-2">Vite</li>
                    </ul>
                </div>

                <div class="col-6 col-lg-2 mb-3">
                    <h5 class="text-black">Projects</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2">Bootstrap 5</li>
                        <li class="mb-2">Bootstrap 4</li>
                        <li class="mb-2">Icons</li>
                        <li class="mb-2">RFS</li>
                        <li class="mb-2">Examples repo</li>
                    </ul>
                </div>

                <div class="col-6 col-lg-2 mb-3">
                    <h5 class="text-black">Community</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2">Issues</li>
                        <li class="mb-2">Discussions</li>
                        <li class="mb-2">Corporate sponsors</li>
                        <li class="mb-2">Open Collective</li>
                        <li class="mb-2">Stack Overflow</li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
import AOS from 'aos';

export default {
    mounted(){
        AOS.init();
    }
}
</script>
<style>
    #logo{
        background-color: #0d0d43;
        border-radius: 50%;
        height: 50px;
        width: 50px;
        margin-right: 15px;
    }
</style>