<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.light.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <div class="logo">
          <v-img src="4d.png" contain max-height="500"></v-img>
          </div>
        </v-col>
        <v-col cols="6">
          <h3 class="black--text text--darken-3 top">Hi! Welcome to Organic's Beauty Tips</h3>
          <h1 class="deep-purple--text text--accent-1">what's your complaint?</h1>
          <p class="grey--text">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. <br />
            Adipisci explicabo, cupiditate necessitatibus iure hic omnis est ab
            <br />
            At nihil et temporibus ratione!
          </p>
          <v-btn tile color="#a69eb0" dark> about me </v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#a69eb0" x-large class="ml-3"
                    >mdi-cart</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Seller</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                    elit.
                  </p>
                  <v-btn color="#a69eb0" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="" x-large class="ml-3" dark
                    >mdi-shopping</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Our Product</h3>
                  <p class="black--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                    elit.
                  </p>
                  <v-btn color="" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#a69eb0" x-large class="ml-3"
                    >mdi-book-open-page-variant</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Branding</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                    elit.
                  </p>
                  <v-btn color="#a69eb0" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="deep-purple--text text--accent-1 mt-4 number">17</h1>
                  <h3 class="deep-purple--text  text--lighten-4 mt-4">Years Experience</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="deep-purple--text text--accent-1">60+</h1>
                        <p class="deep-purple--text  text--lighten-4">Doctors</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="deep-purple--text text--accent-1">138+</h1>
                        <p class="deep-purple--text  text--lighten-4">Clinics</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="deep-purple--text text--accent-1">200+</h1>
                        <p class="deep-purple--text  text--lighten-4">Partners</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="deep-purple--text text--accent-1">90</h1>
                        <p class="deep-purple--text  text--lighten-4">Achievements</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="deep-purple--text  text--lighten-1">NEW ARRIVAL</h4>
          <p class="black--text">Lorem ipsum dolor Lorem ipsum dolor</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#a69eb0" dark> View All </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="package.jpg" contain max-height="200px"></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="serum.jpg" contain max-height="200px"></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="#5d3954" dark text class="ml-n4"> The Package </v-btn
          ><br />

          <v-btn color="#68228b" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="#5d3954" dark text class="ml-n4"> Serum </v-btn><br />

          <v-btn color="#68228b" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="mousturizer.jpg" contain max-height="200px"></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="mist.jpg" contain max-height="200px"></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="#a69eb0" dark text class="ml-n4"> Moisturizing Gel </v-btn
          ><br />

          <v-btn color="#68228b" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="#a69eb0" dark text class="ml-n4"> Mist Water </v-btn><br />
          <v-btn color="#68228b" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="deep-orange--text text--lighten-5">
                    Let's join us!<br />To show your beauty
                  </h1>
                  <p class="grey--text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Eius nesciunt ducimus natus <br />
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn tile color="#a69eb0" dark class="mt-16">
                    Contact
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text>Home</v-btn>
              <v-btn text>Product</v-btn>
              <v-btn text>About</v-btn>
              <v-btn text> contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer/>
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.logo {
  margin-top: 150px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #a69eb0;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>