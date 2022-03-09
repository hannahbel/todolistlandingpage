<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <br />
           <br />
            <br />
          <v-img src="todo.png" contain max-height="1000"></v-img>
        </v-col>
        <v-col cols="6">
          <h4 class="brown--text text--darken-1 top">Got so much important and whimsical stuff to do?</h4>
          <h1 class="orange--text">Keep track of 'em with the To Do List!</h1>
          <p class="black--text">
            It may not be able to ease your workload for it is beyond its power and capability. <br />
            But hey! At least you get to have a beautifully designed, eye-catching task list.
            <br />
            See for yourself. Try it out now!
            
          </p>
          <v-btn tile color="#ea5b38" dark href="https://awesome-lewin-d01bcc.netlify.app/" target="_blank">GO TO APP</v-btn>
           <br />
            <br />
             <br />
              <br />
               <br />
                <br />
                 <br />
                  <br />
                   <br />
        </v-col>

        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#ee7d3b" x-large class="ml-3"
                    >mdi-baby</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Simple to use</h3>
                  <p class="white--text text--darken-4 ml-3 mt-6">
                    Even kids can use it without<br /> asking for
                    parental help.
                  </p>
                  
                </div>
                <div class="child bgColor2">
                  <v-icon color="#ffc252" x-large class="ml-3" dark
                    >mdi-eye</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Pleasing Design</h3>
                  <p class="white--text text--darken-4 ml-3 mt-6">
                   Everyone wants good color <br />choices and attractive visuals.
                  </p>
                  
                </div>
                <div class="child bgColor1">
                  <v-icon color="#ee7d3b" x-large class="ml-3"
                    >mdi-book-open-page-variant</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Familiarity</h3>
                  <p class="white--text text--darken-4 ml-3 mt-6">
                   Just a typical to-do list ...<br />with helpful functionalities!
                  </p>
                  
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="orange--text text--darken-4 mt-4 number">1K+</h1>
                  <h3 class="white--text mt-4">Active Users</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="orange--text text--darken-4">700+</h1>
                        <p class="white--text">Reviews</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="orange--text text--darken-4">55+</h1>
                        <p class="white--text">Collaborations</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="orange--text text--darken-4">16</h1>
                        <p class="white--text">Available Languages</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="orange--text text--darken-4">11</h1>
                        <p class="white--text">Awards</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="orange--text">SCREENSHOTS</h4>
          <p class="grey--text">Still undecided? Take a look first.</p>
        </v-col>
        <v-col md="3" class="text-end">
         <v-btn tile color="#ea5b38" dark href="https://awesome-lewin-d01bcc.netlify.app/" target="_blank"> GO TO APP </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#fce88c"
          >
            <v-img src="1.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#fce88c"
          >
            <v-img src="10.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="red" dark text class="orange--text ml-n4"> Default </v-btn
          ><br />
        </v-col>
        <v-col md="3">
          <v-btn color="red" dark text class="orange--text ml-n4"> Clear completed tasks </v-btn><br />
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#fce88c"
          >
            <v-img src="20.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#fce88c"
          >
            <v-img src="21.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="red" dark text class="ml-n4"> Clear all tasks </v-btn
          ><br />
        </v-col>
        <v-col md="3">
          <v-btn color="red" dark text class="ml-n4"> Empty To-Do List </v-btn><br />
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">
                    We are willing to listen <br />to your feedback.
                  </h1>
                  <p class="white--text text--darken-4">
                    Your comments, suggestions, and honesty
                    shall help us improve a lot. <br />
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn tile color="#ea5b38" dark href="https://www.facebook.com/SaxMast3rH/" target="_blank" class="mt-16">
                    Contact
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#ffffff" dark flat>
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
            
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
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
    #ffc252,
    #ffb224 50%,
    #ffb224 50%,
    #d49724 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #ffb224;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #d68720;
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
  background-color: #f0d24e;
}
.bgColor2 {
  background-color: #ee7d3b;
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