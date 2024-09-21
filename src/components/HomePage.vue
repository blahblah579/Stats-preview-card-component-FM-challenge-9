<template>
  <v-container>
    <v-row class="">
      <v-col
        class="d-flex flex-column-reverse flex-md-row align-center justify-center"
      >
        <v-col cols="" sm="6" class="left pa-10">
          <v-col class="heading">
            Get <span class="insight">insights</span> that help your business
            grow.
          </v-col>
          <v-col class="para">
            Discover the benefits of data analytics and make better decisions
            regarding revenue, customer experience, and overall efficiency.
          </v-col>
          <v-col class="stats d-flex flex-wrap pa-0">
            <v-col cols="12" md="4" class="d-flex flex-column"
              ><span class="t1">10k+</span><span class="t2">COMPANIES</span>
            </v-col>
            <v-col cols="12" md="4" class="d-flex flex-column"
              ><span class="t1">314</span>
              <span class="t2">TEMPLATES</span></v-col
            >
            <v-col cols="12" md="4" class="d-flex flex-column"
              ><span class="t1">12M+</span>
              <span class="t2">QUERIES</span></v-col
            >
          </v-col>
        </v-col>

        <v-col cols="" sm="6" class="right pa-0 d-flex align-center">
          <img
            class="img2"
            src="/src/assets/image-header-desktop.jpg"
            alt="header"
          />
        </v-col>
      </v-col>
    </v-row>
  </v-container>
</template>
  
  
  <style scoped>
@font-face {
  font-family: f1;
  src: url(/src/assets/Inter_18pt-SemiBold.ttf);
}
@font-face {
  font-family: f2;
  src: url(/src/assets/Inter_18pt-Bold.ttf);
}
@font-face {
  font-family: f3;
  src: url(/src/assets/Inter_18pt-Light.ttf);
}
.t1 {
  font-family: f2;
  font-size: 18px;
}
.t2 {
  font-family: f3;
  font-size: 10px;
  letter-spacing: 1px;
  color: hsl(245, 15%, 69%);
}
.heading {
  font-family: f1;
  font-size: 30px;
  color: rgb(255, 255, 255);
  line-height: 2rem;
}
.insight {
  color: hsl(276, 59%, 63%);
}
.para {
  font-size: 13px;
  color: hsl(245, 15%, 69%);
}
.right {
  width: 100%;
  height: 100%;
  position: relative;
}
.right::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: hsla(277, 65%, 39%, 0.6);
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}

.img2 {
  width: 100%; /* Make the image scale to fit the available width */
  height: 100%; /* Make the image scale to fit the available height */
  object-fit: cover; /* Ensures the image covers the entire container */
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}
.left {
  width: 100%;
  height: 100%;
  background-color: hsl(246, 38%, 16%);
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
}

@media (max-width: 960px) {
  .img2 {
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 0px;
  }

  .left {
    border-top-left-radius: 0px;
    border-top-right-radius: 0px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
  }
  .right::before {
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 0px;
  }
  .stats {
    text-align: center;
  }
  .para{
    text-align: center;
  }
}
</style>
  