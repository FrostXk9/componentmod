<template>
 <!-- use bootstrap only for alignment etc. -->
 <!-- no inline styling  -->
 <!-- make sure nav is fully responsive on given width as shown inside the "inspect", if you have questions I will show you what I meant by this -->
 <!-- Okay -->
    <!-- Nav as propsed on figma design -->
    <header class="d-flex justify-content-evenly" id="navBar">


        <svg xmlns="http://www.w3.org/2000/svg" width="793" height="52" viewBox="0 0 793 100" fill="#88CB34" class="svgg">
            <path d="M793 0L395 100L0 0L793 0Z" fill="#88CB34"/>
        </svg>

        <nav class="navbar navbar-expand-lg">

            <div class="container-fluid">

                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">

                <span class="navbar-toggler-icon"></span>
                
                </button>

                <a class="navbar-brand px-3" href="#" id="OnExpand">Twelve Two <span id="shrink">2</span></a>

                <div class="collapse navbar-collapse" id="navbarTogglerDemo03">

                    <ul class="navbar-nav me-auto mb-2 mb-lg-0 gap-5">

                        <li class="nav-item">

                        <router-link to="/" class="nav-link" href="#" id="navText">Home</router-link>

                        </li>
                        
                        <li class="nav-item">

                        <router-link to="/about" class="nav-link" href="#" id="navText">About</router-link>

                        </li>

                        <li class="nav-item">

                        <router-link to="/ourMission" class="nav-link" href="#" id="navText">Our mission</router-link>

                        </li>

                        <li class="nav-item" id="OnShrink">

                            <a class="navbar-brand nav-link mx-3" href="#" id="logoBG"><img src="https://cdn-thumbs.imagevenue.com/f7/b4/d5/ME17IVRQ_t.png" alt="twelve_Two_logo" id="fitLogo" /></a>

                        </li>

                        <li class="nav-item">

                            <router-link to="/Events" class="nav-link" href="#" id="navText">Events</router-link>

                        </li>

                        <li class="nav-item">

                        <router-link to="/" class="nav-link" href="#" id="navText">Products</router-link>

                        </li>

                        <li class="nav-item">

                        <router-link to="/" class="nav-link" href="#" id="navText">Contact</router-link>

                        </li>

                    </ul>

                </div>

            </div>  

        </nav>

    </header>

</template>

<script>
export default {
    
}
</script>

<style scoped>
    *{
        transition: all 0.5s ease-in-out;
    }

    .svgg{
        position: absolute;
        left: 23.9%;
    }

    #logoBG{
        transition: all .3s ease-in-out;
        transform: scale(133%);
    }


    #navText{
        color: rgb(16, 91, 16);
        font-weight: 800;
    }

    #OnExpand{
        display: none;
        color: #0d0d43;
    }
    
    #OnExpand::first-letter{
        color: rgb(0, 216, 0);
    }

    #OnShrink{
        display: block;
    }
    
    #navBar{
        /* background-color: rgb(180, 247, 242); */
        background-color: rgb(255, 255, 255);
        width: 100%;
        position: fixed;
        top: 0;
        height: auto;
        width: 100%;
        z-index: 1;
        /* mix-blend-mode: difference; */
    }

    @media (max-width: 950px) {
        #OnExpand{
            display: block;
        }
        #OnShrink{
            display: none;
        }

        /* issue no.1 */
        .svgg{
            display: none;
        }
        
    }

    #shrink{
        font-size: 10px;
        position: absolute;
        color: rgb(0, 216, 0);
    }

    #fitLogo{
        height: 30px;
        transform: scale(200%);
    }
    
    #logoBG{
        background-color: #101242;
        border-radius: 50%;
    }


    
</style>