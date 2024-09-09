<template>
  <div>
    <a href="https://api.whatsapp.com/send?phone=0201101024741" target="_blank"
      class="btn btn-primary floating-btn">
      <i class="fab fa-whatsapp" style="font-size: 25px;"></i>
    </a>
    <!-- <a href="mailto:website@st-elevator.com" target="_blank"
      class="btn btn-primary floating-btn-2">
      <i class="fa fa-envelope" style="font-size: 25px;"></i>
    </a> -->
    <div class="page-header clear-filter" filter-color="black">
      <!-- <parallax
        class="page-header-image"
        style="background-image:url('img/background.jpg'); transition: all 6s ease-out;"
      >
      </parallax> -->
      <carousel-section class="page-header-image p-0"></carousel-section>
      <div class="container">
        <div class="content-center brand">
          <img class="n-logo" src="img/logo-white.png" alt=""  width="300px" style="max-width: 300px;"/>
          <h2 class="h1-seo" style="font-weight: 500;">Where safety </h2>
          <h3>Meets Elegance</h3>
        </div>
      </div>
    </div>
    <div class="main">
      <div class="section section-images" style="height: auto;">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-md-8">
              <div class="hero-images-container">
                <img src="img/elevator.png" alt="" />
              </div>
              <!-- <div class="hero-images-container-1">
                <img src="img/elevator.png" alt="" />
              </div>
              <div class="hero-images-container-2">
                <img src="img/elevator.png" alt="" />
              </div> -->
            </div>
          </div>
        </div>
      </div>
      <!-- Section About US -->
      <div class="section section-about-us">
        <div class="container">
          <div class="row">
            <div class="col-md-8 ml-auto mr-auto text-center">
              <h2 class="title">Who we are?</h2>
              <h5 class="description text-dark">
                At Streamline Elevator, we are dedicated to revolutionizing the elevator industry and setting
                new standards for vertical transportation solutions. With years of extensive expertise 
                and a commitment to innovation, we strive to deliver safe, efficient, and luxurious 
                elevator systems that enhance the experience of our clients and their users.
              </h5>
            </div>
          </div>
          <div class="separator separator-primary"></div>
          <div class="section-story-overview">
            <div class="row">
              <div class="col-md-6">
                <div
                  class="image-container image-left"
                  style="background-image: url('img/bg-1.jpg')"
                >
                  <!-- First image on the left side -->
                  <p class="blockquote blockquote-primary">
                    "Where Safety Meets Elegance"
                    <br />
                    <br />
                    <small>-CEO</small>
                  </p>
                </div>
                <!-- Second image on the left side of the article -->
                <div
                  class="image-container"
                  style="background-image: url('img/b3.jpg')"
                ></div>
              </div>
              <div class="col-md-5">
                <!-- First image on the right side, above the article -->
                <div
                  class="image-container image-right"
                  style="background-image: url('img/bg-2.jpg')"
                ></div>
                <h3>
                  Our Vision
                </h3>
                <p>
                  To be the first choice of vertical transportation solution provider.
                </p>
                <h3>
                  Our Mission
                </h3>
                <p>
                  Providing the best possible solution to our customers by maintaining high quality
                  performance, perfiction and precision in all what we do.
                </p>
                <h3>
                  What we do
                </h3>
                <p>
                  <ul>
                    <li>
                      Sales, Instullation Testing and Commissioning.
                    </li>
                    <li>
                      Modernization.
                    </li>
                    <li>
                      Maintenance.
                    </li>
                    <li>
                      Lift component trading.
                    </li>
                  </ul>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Section About US -->
      <div class="section section-about-us">
        <div class="container">
          <div class="row">
            <div class="col-md-12 ml-auto mr-auto text-center">
              <h2 class="title">Why choose Streamline Elevator?</h2>
              <div class="row">
                <div class="col-md-4 mb-3">
                  <div class="cookie-card">
                      <span class="title-card">👷‍♂️ 15+ years of experience</span>
                      <p class="description-card text-muted">The core members of the team have more than 15 years of experience in the elevator industry. </p>
                  </div>
                </div>
                <div class="col-md-4 mb-3">
                  <div class="cookie-card">
                      <span class="title-card">📈 Completed Sales System</span>
                      <p class="description-card text-muted">Pre-sales team 1V1 provides customers with the best solutions. Bilingual after-sales engineers are available online to help customers solve after-sales problems at any time.</p>
                  </div>
                </div>
                <div class="col-md-4 mb-3">
                  <div class="cookie-card">
                      <span class="title-card">💡 Keeping pace with the times </span>
                      <p class="description-card text-muted">An experienced team of engineers with the ability to continuously innovate. R&D department regularly introduces advanced materials and technologies. </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="separator separator-primary"></div>
        </div>
      </div>
      <!-- Section of products -->
      <div class="section section-team text-center">
      <div class="container">
        <h2 class="title">Here is our products</h2>
        <div class="team">
          <div class="row">
            <div class="col-md-4">
              <div class="team-player card" style="border-radius: 3rem;">
                <img
                  src="img/shaft.png"
                  alt="Thumbnail Image"
                  class="img-fluid"
                  style="height: 350px;"
                />
                <h4 class="title">Shaftless</h4>
                <p class="category text-primary">Elevator</p>
                <p class="description text-dark">
                  It is a great solution for people who have difficulty climbing stairs. It is ....
                </p>
                <router-link to="/shaftless" class="btn btn-primary btn-round" style="width: fit-content !important; font-weight: 400; font-size: medium;"
                  ><i class="fa fa-eye"> See more</i
                ></router-link>
              </div>
            </div>
            <div class="col-md-4">
              <div class="team-player card" style="border-radius: 3rem;">
                <img
                  src="img/elevator-cartoon.png"
                  alt="Thumbnail Image"
                  class="img-fluid"
                />
                <h4 class="title">Home</h4>
                <p class="category text-primary">Elevator</p>
                <p class="description text-dark">
                  Whether you've decided to build your dream home or enjoy the freedom  ....
                </p>
                <router-link to="/home" class="btn btn-primary btn-round" style="width: fit-content !important; font-weight: 400; font-size: medium;"
                  ><i class="fa fa-eye"> See more</i
                ></router-link>
              </div>
            </div>
            <div class="col-md-4">
              <div class="team-player card" style="border-radius: 3rem;">
                <img
                  src="img/elevator.png"
                  alt="Thumbnail Image"
                  class="img-fluid"
                />
                <h4 class="title">Passenger</h4>
                <p class="category text-primary">Elevator</p>
                <p class="description text-dark">
                  Streamline Elevator's Passenger Elevators offer safety, efficiency, and  ....
                </p>
                <router-link to="/shaftless" class="btn btn-primary btn-round" style="width: fit-content !important; font-weight: 400; font-size: medium;"
                  ><i class="fa fa-eye"> See more</i
                ></router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
      <!-- Section to add -->
      <div class="section section-contact-us text-center">
        <div class="container">
          <h2 class="title">Want to know more?</h2>
          <p class="description">You can leave us a message.</p>
          <div class="row">
            <div class="col-lg-6 text-center ml-auto mr-auto col-md-8">
              <fg-input
                class="input-lg"
                placeholder="Your Name..."
                v-model="form.Name"
                addon-left-icon="now-ui-icons users_circle-08"
              >
              </fg-input>
              <fg-input
                class="input-lg"
                placeholder="Email Here..."
                v-model="form.email"
                addon-left-icon="now-ui-icons ui-1_email-85"
              >
              </fg-input>
              <fg-input
                class="input-lg"
                placeholder="Phone Number..."
                v-model="form.phone"
                addon-left-icon="now-ui-icons tech_headphones"
              >
              </fg-input>
              <div class="textarea-container">
                <textarea
                  class="form-control"
                  name="name"
                  rows="4"
                  cols="80"
                  v-model="form.message"
                  placeholder="Type a message..."
                ></textarea>
              </div>
              <div class="send-button">
                <n-button type="primary" round block size="lg" @click="SubmitForm"
                  >Send Message</n-button
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Parallax, Button, FormGroupInput } from '@/components';
import CarouselSection from './components/CarouselSection';
import axios from 'axios';
import Swal from 'sweetalert2';

export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    // Parallax,
    CarouselSection,
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput
  },
  data() {
    return {
      form: {
        Name: '',
        email: '',
        message: '',
        phone:''
      }
    };
  },
  methods:{
    async SubmitForm(){
      await axios.post("https://formspree.io/f/xknddwpe",this.form).then(res =>{
        Swal.fire({
          title: 'Email sent',
          text: 'We will contact you soon!',
          icon: 'success',
          confirmButtonText: 'Ok'
        })
        this.form = {
          Name: '',
          email: '',
          message: '',
          phone: ''
        }
      }).catch(err =>{
        console.log(err);
        Swal.fire({
          title: 'Email not sent',
          text: err.response.data.errors[0].message,
          icon: 'error',
          confirmButtonText: 'Ops'
        })
      });
    }
  }
};
</script>
<style scoped>
.floating-btn {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 1000;
  border-radius: 25rem;
  background-color: #26d969;
  animation: bounce 1s infinite alternate;
}
.floating-btn-2 {
  position: fixed;
  bottom: 20px;
  right: 100px;
  z-index: 1000;
  border-radius: 25rem;
  background-color: #2671d9;
  animation: bounce 1s infinite alternate;
}
@keyframes bounce {
  to { transform: scale(1.2); }
}

.cookie-card {
  max-width: 320px;
  padding: 1rem;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 20px 20px 30px rgba(0, 0, 0, .05);
}

.title-card {
  font-weight: 600;
  font-size: large;
  color: rgb(31 41 55);
}

.description-card {
  margin-top: 1rem;
  font-size: 1rem;
  line-height: 1.25rem;
  font-weight: 400;
  color: black;
}

.description-card a {
  --tw-text-opacity: 1;
  color: rgb(59 130 246);
}

.description-card a:hover {
  -webkit-text-decoration-line: underline;
  text-decoration-line: underline;
}

.actions {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 1rem;
  -moz-column-gap: 1rem;
  column-gap: 1rem;
  flex-shrink: 0;
}

.pref {
  font-size: 0.75rem;
  line-height: 1rem;
  color: rgb(31 41 55 );
  -webkit-text-decoration-line: underline;
  text-decoration-line: underline;
  transition: all .3s cubic-bezier(0.4, 0, 0.2, 1);
  border: none;
  background-color: transparent;
}

.pref:hover {
  color: rgb(156 163 175);
}

.pref:focus {
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.accept {
  font-size: 0.75rem;
  line-height: 1rem;
  background-color: rgb(17 24 39);
  font-weight: 500;
  border-radius: 0.5rem;
  color: #fff;
  padding-left: 1rem;
  padding-right: 1rem;
  padding-top: 0.625rem;
  padding-bottom: 0.625rem;
  border: none;
  transition: all .15s cubic-bezier(0.4, 0, 0.2, 1);
}

.accept:hover {
  background-color: rgb(55 65 81);
}

.accept:focus {
  outline: 2px solid transparent;
  outline-offset: 2px;
}
</style>