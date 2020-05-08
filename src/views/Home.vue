<template>
  <div id="body1">
    <v-container grid-list-md id="body">
      <v-layout row wrap>
        <v-flex xs12 sm12>
          <v-img id="profile" src="@/assets/logo.jpg" alt="picture" />
        </v-flex>
        <v-flex xs12 sm12>
          <br />
          <h2 style="text-align:left">
            HELLO I'M
            <h1>HAYA BARAKAT</h1>
            <br />MULTIMEDIA DESIGNER
          </h2>
          <br />
          <v-btn>
            <a
              href="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/CV-April-2020-Eng.pdf?alt=media&token=86e057e0-d389-4eeb-9ede-d700aefb107f"
              target="_blank"
            >VIEW MY RESUME</a>
          </v-btn>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container grid-list-md id="recent-work">
      <v-layout row wrap>
        <v-flex xs12 class="mb-2">
          <h3 style="text-align:start">Recent Work</h3>
          <v-divider></v-divider>
        </v-flex>
        <v-flex xs12 sm6 class="mb-2">
          <v-card>
            <v-img
              src="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/Space.svg?alt=media&token=8cc2e822-448a-40bc-a7c6-b8675b6eb659"
              height="400px"
            ></v-img>

            <v-card-title primary-title>
              <div>
                <div class="headline">Illustration</div>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon @click="show = !show">
                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
              </v-btn>
            </v-card-actions>

            <v-slide-y-transition>
              <v-card-text
                v-show="show"
              >Asteroid belt around Jupiter and the difference between asteroids, comets, meteoroids, and meteors. Adobe Illustrator</v-card-text>
            </v-slide-y-transition>
          </v-card>
        </v-flex>
        <v-flex xs12 sm6 class="mb-2">
          <v-card>
            <v-img
              src="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/astroits%20belt.svg?alt=media&token=9559f8ed-554d-4254-ade2-d917d1febb61"
              height="400px"
            ></v-img>

            <v-card-title primary-title>
              <div>
                <div class="headline">Illustration of Asteroit Belt</div>
              </div>
            </v-card-title>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon @click="show = !show">
                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
              </v-btn>
            </v-card-actions>

            <v-slide-y-transition>
              <v-card-text
                v-show="show"
              >Zoomed view of Jupiter and the asteroid belt around it. Adobe Illustrator</v-card-text>
            </v-slide-y-transition>
          </v-card>
        </v-flex>

        <v-flex xs12 sm6 class="mb-2">
          <v-card>
            <v-img
              src="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/MiniMe.svg?alt=media&token=828c117d-fd76-42c7-bfe5-9abcd845505d"
              contain
              height="400px"
            ></v-img>

            <v-card-title primary-title>
              <div>
                <div class="headline">Mini Me Assignment</div>
              </div>
            </v-card-title>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon @click="show = !show">
                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
              </v-btn>
            </v-card-actions>

            <v-slide-y-transition>
              <v-card-text
                v-show="show"
              >Contant Creation Mini-Me first semester assignment. Adobe Illustrator</v-card-text>
            </v-slide-y-transition>
          </v-card>
        </v-flex>
        <v-flex xs12 sm6 class="mb-2">
          <v-card>
            <v-img
              class="astroit"
              src="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/exposureEffect.jpg?alt=media&token=0a261178-9554-4b72-b650-07a5b65c921d"
              contain
              height="400px"
            ></v-img>

            <v-card-title primary-title>
              <div>
                <div class="headline">Double Exposure Effect</div>
              </div>
            </v-card-title>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon @click="show = !show">
                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
              </v-btn>
            </v-card-actions>

            <v-slide-y-transition>
              <v-card-text
                v-show="show"
              >Double expoture effect first semester assignment. Adobe Photoshop</v-card-text>
            </v-slide-y-transition>
          </v-card>
        </v-flex>

        <v-flex xs12 sm6 class="mb-2">
          <v-card>
            <iframe
              width="443.333"
              height="315"
              src="https://www.youtube.com/embed/TKyBcoYSyoo"
              frameborder="0"
              allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
            <v-card-title primary-title>
              <div>
                <div class="headline">Corona Pendemic</div>
              </div>
            </v-card-title>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon @click="show = !show">
                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
              </v-btn>
            </v-card-actions>

            <v-slide-y-transition>
              <v-card-text
                v-show="show"
              >Animated clip of Earth affected with Covide-19. Created with Premire Pro.</v-card-text>
            </v-slide-y-transition>
          </v-card>
        </v-flex>

        <v-flex xs12 sm6 class="mb-2">
          <v-card>
            <iframe
              width="443.333"
              height="315"
              src="https://www.youtube.com/embed/ogJ5nNb3cpY"
              frameborder="0"
              allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
            <v-card-title primary-title>
              <div>
                <div class="headline">Video CV 2020</div>
              </div>
            </v-card-title>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon @click="show = !show">
                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
              </v-btn>
            </v-card-actions>

            <v-slide-y-transition>
              <v-card-text v-show="show">Premire Pro and After Effects</v-card-text>
            </v-slide-y-transition>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show: false,
      reviews: 413,
      value: 4.5
    };
  }
};
</script>

<style lang="scss" scoped>
@import "./src/scss/variables.scss";

#body1 {
  background-image: linear-gradient(
    160deg,
    rgb(230, 228, 228) 20%,
    #00000059,
    #f0c1b6
  );
}

#body {
  background-image: linear-gradient(
    170deg,
    rgb(230, 228, 228) 50%,
    #00000059 10%,
    #f0c1b6
  );
}

#recent-work {
  margin-top: 50px;
}

#profile {
  padding: 20px;
  justify-self: flex-start;
}

a {
  text-decoration: none;
  color: #000000;
}
</style>
