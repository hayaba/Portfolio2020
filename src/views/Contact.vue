<template>
  <div id="body">
    <v-container class="grey lighten-5">
      <v-row>
        <v-col cols="12" sm="12" md="12">
          <v-card class="pa-2">
            <h1>CONTACT</h1>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="info" cols="6" sm="6" md="8">
          <v-card id="card" class="pa-2" height="1080px">
            <h2>Say Hello!</h2>
            <br />
            <h4 id="contact-mail">{{ email }}</h4>
            <br />

            <h4 id="address">{{ city }}</h4>
            <br />

            <v-btn>
              <a
                href="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/Business%20Card.04.2020.pdf?alt=media&token=df803b35-5dc5-4224-847b-5702e68eff3f"
                target="_blank"
              >MY BUSINESS CARD</a>
            </v-btn>

            <v-btn>
              <a
                href="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/CV-April-2020-Eng.pdf?alt=media&token=86e057e0-d389-4eeb-9ede-d700aefb107f"
                target="_blank"
              >VIEW MY RESUME</a>
            </v-btn>

            <br />
            <a href="https://www.linkedin.com/in/haya-barakat" target="_blank">
              <i class="fab fa-linkedin-in"></i>
            </a>

            <a href="https://www.instagram.com/hayabarakat95/" target="_blank">
              <i class="fab fa-instagram"></i>
            </a>
            <a href="https://www.facebook.com" target="_blank">
              <i class="fab fa-facebook-f"></i>
            </a>

            <br />
          </v-card>
        </v-col>

        <v-col cols="6" md="4">
          <v-card id="card" class="pa-2">
            <v-img
              src="https://firebasestorage.googleapis.com/v0/b/portfolio-452e1.appspot.com/o/MiniMe.svg?alt=media&token=828c117d-fd76-42c7-bfe5-9abcd845505d"
              alt="minime"
              height="1080px"
            />
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "CONTACTS",
      email: "E-mail: Haya0183@easv365.dk",
      city: "Esbjerg, Denmark"
    };
  }
};
</script>

<style lang="scss" scoped>
@import "./src/scss/variables.scss";

#body {
  background-image: linear-gradient(
    170deg,
    rgb(230, 228, 228) 50%,
    #00000059 10%,
    #f0c1b6
  );
}

h1 {
  background-color: map-get($colors2, colors11);
  padding: 20px;
  color: map-get($colors, colors1);
}

h2 {
  padding-top: 120px;
}

#address {
  margin-bottom: 20px;
}

#contact-mail {
  padding: 20px 0;
  font-size: 20px;
}

#card {
  background-color: #f3f3f3;
  text-align: center;
}

.v-btn {
  margin: 10px;
}

a {
  text-decoration: none;
  color: #000000;
}

i {
  margin: 20px 0;
  padding: 20px;
  font-size: 50px;
}

i:hover {
  color: #df755d;
}
</style>