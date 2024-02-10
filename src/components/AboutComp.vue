<template >
    
  <h2 id="txt" class="pt-2">About Us</h2>

  <span class="ul" data-aos="fade-right" data-aos-anchor-placement="center" ></span>

  <div class="row bg-body-tertiary pt-5 mt-4 px-1" id="abt">

    <div class="container my-5">

      <div class="row p-4 pb-0 pe-lg-0 pt-lg-5 align-items-center rounded-3 border shadow-sm">

        <div class="col-lg-7 p-3 p-lg-5 pt-lg-3">

          <h1 class="display-4 fw-bold lh-1 text-body-emphasis">Grow with Twelve Two</h1>

          <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore commodi nostrum consequatur vel fugiat voluptates nihil. Placeat odio maiores porro ipsam nemo nam unde, corporis debitis reiciendis veniam, facilis repellendus.</p>

          <div class="d-grid gap-2 d-md-flex justify-content-md-center mb-4 mb-lg-3">

            <button type="button" class="btn btn-outline-secondary btn-lg px-4 me-md-2 fw-bold">Primary</button>

            <button type="button" class="btn btn-outline-secondary btn-lg px-4 me-md-2 fw-bold">Default</button>
            
          </div>


          <div class="d-flex justify-content-evenly pt-5 flex-wrap" id="marketingBox">

            <div id="boxOne">Expert advice about how to save money</div>

            <div id="boxTwo">Understand more about finance</div>
            
            <div id="boxThree">Know how to grow your income</div>
          </div>


        </div>


        <div class="col-lg-4 offset-lg-1 p-0 overflow-hidden shadow">
          <div id="vid">
            <video class="border border-black shadow" autoplay muted loop src="../assets/pexels_videos_1448735 (2160p).mp4" type="video/mp4" id="vd" width="720">

            </video>
          </div>
        </div>
      </div>
    </div>
    <div class="col-lg-4 pt-5">

      <div id="boxed" class="bd-placeholder-img rounded-circle">

        <i class="fa-solid fa-dollar-sign fa-2xl" style="color: #000000;" id="scaleIcon"></i>
            
      </div>
          
      <h2 class="fw-bold">Financial Growth</h2>
          
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minus, possimus libero repellendus mollitia repellat animi officia eius vel ipsa architecto laudantium velit, reiciendis dolore eaque sunt dolor aliquam tempora voluptatem?</p>

      </div>

      <div class="col-lg-4 pt-5">

        <div id="boxed" class="bd-placeholder-img rounded-circle">

          <i class="fa-solid fa-check-double fa-2xl" style="color: #000000;" id="scaleIcon"></i>

        </div>

        <h2 class="fw-bold">Guaranteed Knowledge</h2>

        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Unde officia deserunt dolorem eius perspiciatis praesentium, rerum dolor nobis aut laboriosam est libero totam voluptatibus vitae quia repudiandae excepturi laborum beatae!</p>

      </div>

      <div class="col-lg-4 pt-5">

        <div id="boxed" class="bd-placeholder-img rounded-circle">

          <i class="fa-solid fa-money-bill-trend-up fa-2xl" style="color: #000000;" id="scaleIcon"></i>

        </div>

        <h2 class="fw-bold">Improvement</h2>

        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Enim, rem blanditiis ipsam deleniti itaque, esse id fuga ipsa odit dolorum voluptates praesentium numquam harum ratione vero provident. Eligendi, ab itaque?</p>

      </div>



  </div>

    <div id="bottomSec"></div>
  
</template>
  <script>
  export default {
      
  }
  </script>
  <style>

    #txt{
      position: absolute;
      top: 7%;
      left: 0.3%;
      color: rgb(0, 0, 0);
    }

    #bottomSec{
      min-height: 100vh;
    }

    #abt{
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 50vh;
      background-color: rgb(219, 240, 219) !important;
    }

    .ul{
      height: 5px;
      width: 90px;
      background-color: rgb(133, 247, 107);
      position: absolute;
      box-shadow: 2px 2px 7px 2px rgba(0, 0, 0, 0.349);
      top: 12.6%;
      left: 0.3%;
    }

    #boxOne,#boxTwo,#boxThree{
      background-color: rgb(201, 240, 255);
      border-radius: 10px;
      font-weight: 600;
      width: 200px;
      height: 50px;
      padding-top: 4px;
      padding-bottom: 4px;
      padding-left: 4px;
      padding-right: 4px;
      text-align: center;
      border: 1px solid whitesmoke;
      box-shadow: 3px 3px 10px 1px rgba(22, 22, 22, 0.237);
    }

    [data-boxed]{
      min-height: 50vh;
      background-image: url("https://cdn-images.imagevenue.com/0c/da/8c/ME17KQ92_o.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      filter: grayscale();
    }

    #scaleIcon{
      transform: scale(150%);
      margin-bottom: 30px;
      padding: 25px;
      border-radius: 50%;
    }

    #scaleIcon:hover{
      transform: scale(170%);
      transition: all 0.1s ease-in-out;
    }

  </style>