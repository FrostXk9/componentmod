<template>
<!-- data-aos="fade-up" data-aos-anchor-placement="center-center" -->
  <div class="position-relative overflow-hidden p-3 text-center" id="landingPage">

    <div class="col-md-6 p-lg-5 mx-auto">
      
      <div id="rotate">
        <div class="rtpov">
          <p class="text-decoration-underline fw-bold">We Teach</p>
          <div class="words">
            <span class="word">Innovative</span>
            <span class="word">Excelence</span>
            <span class="word">Growth</span>
            <span class="word">Finance</span>
            <span class="word">Resillience</span>
          </div>
        </div>
      </div>

      <div class="display-1 fw-bold text-black my-3" id="fontify">Twelve Two <span id="floatLikeInt">2</span></div>
      <!-- <p class="text-end mx-5 px-5 fw-bold small">A mindset is all you need</p> -->

        <p class="fw-normal text-black text-center mb-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla eius totam possimus maxime? Ipsa quo illo vitae vero eum, repellat commodi inventore omnis rem molestias quaerat quisquam suscipit incidunt! Tempora!</p>

      <div class="d-flex gap-3 justify-content-center lead fw-normal">

        <ButtonComp />

      </div>

      
    </div>

    <div class="container">
      <h3>Stay updated with us <i class="fa-regular fa-calendar-check fa-lg" style="color: #000000;"></i></h3>
      <p class="small text-center text-black-50">Build your knowledge in money</p>
    </div>

    <div class="container-fluid my-0 mx-4 p-1 d-flex justify-content-evenly" id="iconBox">

      <div class="d-flex">
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="61" viewBox="0 0 54 61" fill="none">
      
          <path d="M53.0281 10.7168C49.1527 6.22382 44.032 2.98097 38.3135 1.3983C32.595 -0.184371 26.5357 -0.0357775 20.9017 1.82529C15.2676 3.68636 10.312 7.17631 6.66145 11.8538C3.01089 16.5313 0.829356 22.1863 0.392713 28.1037C-0.0439294 34.021 1.28393 39.935 4.20838 45.0977C7.13283 50.2603 11.5225 54.4399 16.8223 57.1078C22.1222 59.7756 28.0941 60.812 33.9829 60.0859C39.8718 59.3597 45.413 56.9036 49.906 53.0281L44.0946 46.2908C40.9342 49.0168 37.0363 50.7445 32.894 51.2553C28.7517 51.7661 24.5509 51.0371 20.8229 49.1605C17.0949 47.2838 14.0071 44.3439 11.95 40.7123C9.89292 37.0808 8.95888 32.9208 9.26602 28.7584C9.57316 24.5961 11.1077 20.6182 13.6756 17.328C16.2434 14.0377 19.7293 11.5828 23.6924 10.2737C27.6555 8.96461 31.9177 8.86009 35.9402 9.97337C39.9627 11.0867 43.5647 13.3677 46.2908 16.5282L53.0281 10.7168Z" fill="#88CB34"/>
          
        </svg>

        <div id="text">Check out latest Events
          <div>
            <button class="btn mt-1" id="btn">Book Event</button>
          </div>
        </div>

      </div>

      <div class="d-flex">
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="61" viewBox="0 0 54 61" fill="none">
      
          <path d="M53.0281 10.7168C49.1527 6.22382 44.032 2.98097 38.3135 1.3983C32.595 -0.184371 26.5357 -0.0357775 20.9017 1.82529C15.2676 3.68636 10.312 7.17631 6.66145 11.8538C3.01089 16.5313 0.829356 22.1863 0.392713 28.1037C-0.0439294 34.021 1.28393 39.935 4.20838 45.0977C7.13283 50.2603 11.5225 54.4399 16.8223 57.1078C22.1222 59.7756 28.0941 60.812 33.9829 60.0859C39.8718 59.3597 45.413 56.9036 49.906 53.0281L44.0946 46.2908C40.9342 49.0168 37.0363 50.7445 32.894 51.2553C28.7517 51.7661 24.5509 51.0371 20.8229 49.1605C17.0949 47.2838 14.0071 44.3439 11.95 40.7123C9.89292 37.0808 8.95888 32.9208 9.26602 28.7584C9.57316 24.5961 11.1077 20.6182 13.6756 17.328C16.2434 14.0377 19.7293 11.5828 23.6924 10.2737C27.6555 8.96461 31.9177 8.86009 35.9402 9.97337C39.9627 11.0867 43.5647 13.3677 46.2908 16.5282L53.0281 10.7168Z" fill="#88CB34"/>
          
        </svg>
        <div id="text">Webinars happening:
          <div>
            <button class="btn mt-1" id="btn">View Live</button>
          </div>
        </div>
      </div>

      <div class="d-flex">
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="61" viewBox="0 0 54 61" fill="none">
      
          <path d="M53.0281 10.7168C49.1527 6.22382 44.032 2.98097 38.3135 1.3983C32.595 -0.184371 26.5357 -0.0357775 20.9017 1.82529C15.2676 3.68636 10.312 7.17631 6.66145 11.8538C3.01089 16.5313 0.829356 22.1863 0.392713 28.1037C-0.0439294 34.021 1.28393 39.935 4.20838 45.0977C7.13283 50.2603 11.5225 54.4399 16.8223 57.1078C22.1222 59.7756 28.0941 60.812 33.9829 60.0859C39.8718 59.3597 45.413 56.9036 49.906 53.0281L44.0946 46.2908C40.9342 49.0168 37.0363 50.7445 32.894 51.2553C28.7517 51.7661 24.5509 51.0371 20.8229 49.1605C17.0949 47.2838 14.0071 44.3439 11.95 40.7123C9.89292 37.0808 8.95888 32.9208 9.26602 28.7584C9.57316 24.5961 11.1077 20.6182 13.6756 17.328C16.2434 14.0377 19.7293 11.5828 23.6924 10.2737C27.6555 8.96461 31.9177 8.86009 35.9402 9.97337C39.9627 11.0867 43.5647 13.3677 46.2908 16.5282L53.0281 10.7168Z" fill="#88CB34"/>
          
        </svg>
        <div id="text">Our new Products:
          <div>
            <button class="btn mt-1" id="btn">View shop</button>
          </div>
        </div>
      </div>
    </div>
    
  </div>
    
</template>

<script>

import AOS from 'aos';
import ButtonComp from './ButtonComp.vue';
import ImageLoader from './ImageLoader.vue';

export default {
  components : {
    ButtonComp,
    ImageLoader
  },
  
  mounted(){
    AOS.init()
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#landingPage{
  background-image: url("https://cdn-images.imagevenue.com/8d/4d/d7/ME17JAM6_o.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}


#fontify{
  /* background-color: rgba(255, 255, 255, 0.266);
  -webkit-backdrop-filter: blur(2px);
  backdrop-filter: blur(2px);
  border-radius: 30px;
  box-shadow: 2px 2px 20px 2px rgba(0, 0, 0, 0.241); */
  background: linear-gradient(to right,#136e03, rgb(55, 255, 0));
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

#btn{
  font-weight: 600;
}


#btn:hover{
  color: rgb(53, 230, 3);
  background-color: rgba(245, 245, 245, 0.214);
  -webkit-backdrop-filter: blur(2px);
  backdrop-filter: blur(2px);
  transform: scale(100.5%);
}


#rotate {
  --bg-color: #21212100;
  display: flex;
  justify-content: center;
}

#floatLikeInt{
  position: absolute;
  font-size: 30px;
  font-weight: 800;
  text-decoration: underline green;
  background: linear-gradient(to right,#59ff00, rgb(7, 105, 0));
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

.rtpov {
  color: rgb(0, 0, 0);
  font-family: "Poppins", sans-serif;
  font-weight: 700;
  font-size: 20px;
  -webkit-box-sizing: content-box;
  box-sizing: content-box;
  height: 40px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.words {
  overflow: hidden;
  position: relative;
}

.word {
  display: block;
  height: 100%;
  padding-left: 6px;
  color: rgb(0, 216, 0);
  animation: spin_4991 4s infinite;
  font-weight: 700;
}

@keyframes spin_4991 {
  10% {
    -webkit-transform: translateY(-102%);
    transform: translateY(-102%);
  }

  25% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
  }

  35% {
    -webkit-transform: translateY(-202%);
    transform: translateY(-202%);
  }

  50% {
    -webkit-transform: translateY(-200%);
    transform: translateY(-200%);
  }

  60% {
    -webkit-transform: translateY(-302%);
    transform: translateY(-302%);
  }

  75% {
    -webkit-transform: translateY(-300%);
    transform: translateY(-300%);
  }

  85% {
    -webkit-transform: translateY(-402%);
    transform: translateY(-402%);
  }

  100% {
    -webkit-transform: translateY(-400%);
    transform: translateY(-400%);
  }
}

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}
#landingPage{
  background-color: rgba(0, 0, 0, 0);
  min-height: 100vh;
  width: 100%;
}
a {
  color: #42b983;
}

#text{
  padding: 17px  0px;
  color: rgb(0, 0, 0);
  font-weight: bold;
}

/* Media queries */

@media (max-width: 550px) {
  #iconBox{
    display: flex;
    flex-direction: column;
    padding-left: 120px !important;
  }

  #landingPage{
    padding-top: 70px !important;
  }
}


@media (max-width: 450px) {
  #iconBox{
    display: flex;
    flex-direction: column;
    padding-left: 60px !important;
  }

  #landingPage{
    padding-top: 70px !important;
  }
}


@media (max-width: 325px) {
  #iconBox{
    display: flex;
    flex-direction: column;
    padding-left: 20px !important;
  }

  #landingPage{
    padding-top: 70px !important;
  }
}

</style>
