<template>
  <div class="wrapper">
    <parallax class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout">
          <div
            class="md-layout-item md-size-70 md-small-size-70 md-xsmall-size-100"
          >
            <h1 class="title"> If You Love Travel. <br>
              Travel Freedom Is Here
            </h1>

            <div class="lineTop"></div>

            <h3>
              Experience Travel-As-A-Service With Our
              <br> End-To-End Trip Planning Platform
            </h3>

            <br />
            <md-button
              href="#"
              class="md-lg topBut"
              target="_blank"
              > GET EARLY ACCESS  > </md-button
            >
          </div>
        </div>
      </div>
    </parallax>
    <div class="main">
      <div class="section" id="thumbSec">
        <div class="container">
          <div class="features text-center">
            <div class="md-layout">
              <div class="md-layout-item md-medium-size-25 md-small-size-100">
                <div class="info travelInfo">
                 <h3 class="travelText"> Experience Travel Differently</h3>
                    <p> Tute enim adipisicing eu occaecat enim eu eu represnt. </p>

                    <md-button
                    class="md-lg getBut"
                    >
                        Get  Started
                    </md-button>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-25 md-small-size-100">
                  <div class="w-full sm:w-1/2 md:w-1/3 flex flex-col">
                      <div class="bg-white rounded-lg shadow-lg overflow-hidden flex-1 flex flex-col">
                          <div class="bg-cover h-48" :style="thirdStyle"></div>
                          <div class="p-4 flex-1 flex flex-col" style="padding-top:5px; text-align: left">
                              <h3 class="mb-4 text-2xl" style="margin-bottom: 5px !important; font-weight: 700">EARN MONEY</h3>
                              <div class="mb-4 text-grey-darker text-sm flex-1">
                                  <p>Magna Velit Proident Magna Eiusmod Commodo aliqua ea </p>
                              </div>

                          </div>
                      </div>
                  </div>

              </div>
              <div class="md-layout-item md-medium-size-25 md-small-size-100">
                       <div class="w-full sm:w-1/2 md:w-1/3 flex flex-col">
                      <div class="bg-white rounded-lg shadow-lg overflow-hidden flex-1 flex flex-col">
                          <div class="bg-cover h-48" :style="thirdStyle"></div>
                          <div class="p-4 flex-1 flex flex-col" style="padding-top:5px; text-align: left">
                              <h3 class="mb-4 text-2xl" style="margin-bottom: 5px !important; font-weight: 700">EARN MONEY</h3>
                              <div class="mb-4 text-grey-darker text-sm flex-1">
                                  <p>Magna Velit Proident Magna Eiusmod Commodo aliqua ea </p>
                              </div>

                          </div>
                      </div>
                  </div>
              </div>
              <div class="md-layout-item md-medium-size-25 md-small-size-100">
                  <div class="w-full sm:w-1/2 md:w-1/3 flex flex-col">
                      <div class="bg-white rounded-lg shadow-lg overflow-hidden flex-1 flex flex-col">
                          <div class="bg-cover h-48" :style="thirdStyle"></div>
                          <div class="p-4 flex-1 flex flex-col" style="padding-top:5px; text-align: left">
                              <h3 class="mb-4 text-2xl" style="margin-bottom: 5px !important; font-weight: 700">EARN MONEY</h3>
                              <div class="mb-4 text-grey-darker text-sm flex-1">
                                  <p>Magna Velit Proident Magna Eiusmod Commodo aliqua ea </p>
                              </div>

                          </div>
                      </div>
                  </div>

              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="vector"></div>
      <div class="section text-center">
        <div class="container">
          <h2 class="title">Here is our team</h2>
          <div class="team">
            <div class="md-layout">
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg1"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      Gigi Hadid
                      <br />
                      <small class="card-description text-muted">Model</small>
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-facebook-square"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg2"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      Carla Hortensia
                      <br />
                      <small class="card-description text-muted"
                        >Designer</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-linkedin"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg3"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      Kendall Jenner
                      <br />
                      <small class="card-description text-muted">Model</small>
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple"
                      >
                        <i class="fab fa-facebook-square"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="section section-contacts">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto">
              <h2 class="text-center title">Work with us</h2>
              <h4 class="text-center description">
                Divide details about your product or agency work into parts.
                Write a few lines about each one and contact us about any
                further collaboration. We will responde get back to you in a
                couple of hours.
              </h4>
              <form class="contact-form">
                <div class="md-layout">
                  <div class="md-layout-item md-size-50">
                    <md-field>
                      <label>Your Name</label>
                      <md-input v-model="name" type="text"></md-input>
                    </md-field>
                  </div>
                  <div class="md-layout-item md-size-50">
                    <md-field>
                      <label>Your Email</label>
                      <md-input v-model="email" type="email"></md-input>
                    </md-field>
                  </div>
                </div>
                <md-field maxlength="5">
                  <label>Your Message</label>
                  <md-textarea v-model="message"></md-textarea>
                </md-field>
                <div class="md-layout">
                  <div class="md-layout-item md-size-33 mx-auto text-center">
                    <md-button class="md-success">Send Message</md-button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    import {
        mdbRow,
        mdbBtn,
        mdbCard,
        mdbCardBody,
        mdbCardImage,
        mdbCardText,
        mdbCardTitle,
        mdbCardGroup,
        mdbContainer
    } from "mdbvue";
export default {
  bodyClass: "landing-page",
  props: {
    header: {
      type: String,
      default: require("@/assets/img/atopimage.jpg")
    },
    teamImg1: {
      type: String,
      default: require("@/assets/img/faces/avatar.jpg")
    },
    teamImg2: {
      type: String,
      default: require("@/assets/img/faces/christian.jpg")
    },
    teamImg3: {
      type: String,
      default: require("@/assets/img/faces/kendall.jpg")
    },
     thirdImg: {
      type: String,
      default: require("@/assets/img/thirdimg.png")
    }
  },
  data() {
    return {
      name: null,
      email: null,
      message: null
    };
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`
      };
    },
    thirdStyle() {
      return {
        backgroundImage: `url(${this.thirdImg})`,
        height: `220px`,
        backgroundRepeat: `no-repeat`
      };
    }
  }
};
</script>

<style lang="scss" scoped>
.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
.contact-form {
  margin-top: 30px;
}

.md-has-textarea + .md-layout {
  margin-top: 15px;
}
  .topBut{
    background: white !important;
    font-family: Campton;
    font-size: 12px;
    line-height: 16px;
    letter-spacing: 0.02em !important;
    text-transform: uppercase;
    color: #039785 !important;
  }

  .lineTop{
    width: 55px;
    border: 4px solid #FFFFFF;
  }
    .getBut{
        background: #039785 !important;
        color: #ffffff !important;
    }
    .travelText{
      font-weight: 700;
      text-align: left !important;
    }
    .travelInfo{
      text-align:left !important;
    }
    #thumbSec{
        background: url(../assets/img/contact_map.png);
    height: 100%;
    z-index: -1;
    padding-bottom: 100px;
    padding-top: 70px;
    }
    #vector{
       background: url(../assets/img/vector4.png);
    height: 100px;
    }
</style>
