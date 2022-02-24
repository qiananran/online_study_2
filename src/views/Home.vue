<template>
  <div>
    <v-app-bar
      style="
        padding: 0px 90px;
        display: flex;
        justify-content: center;
        align-items: center;
      "
      app
      color="#FFFFFF"
      light
      elevation="0"
    >
      <div class="d-flex align-center">
        <v-img
          alt="Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.jsdelivr.net/gh/qiananran/myImage/onlinestudy/Component.png"
          transition="scale-transition"
          width="40"
        />
      </div>
      <div class="my_bar">
        <div>
          <v-btn
            text
            v-for="(text, index) in btnText"
            :key="index"
            class="mr-7"
          >
            <span class="my_bartext">{{ text }}</span>
          </v-btn>
        </div>
        <div>
          <v-btn class="btn_login" color="white" width="110px" height="45px"
            >登录</v-btn
          >
          <v-btn
            style="
              color: white;
              background: linear-gradient(35deg,#1028ff 15.75%,#ff067e 84.63%);
              border-radius: 80px;
              margin-left: 20px;
            "
            color="#4461F2"
            height="45px"
            width="135px"
            >快速开始</v-btn
          >
        </div>
      </div>
    </v-app-bar>

    <v-main style="padding: 0; height: 100%" class="overflow-hidden">
      <div>
        <div
          style="
            display: flex;
            justify-content: space-between;
            align-items: center;
          "
        >
          <v-card
            min-width=" 1090"
            min-height="675"
            elevation="0"
            style="
              border-radius: 0px 20px 20px 0px;
              background: linear-gradient(222.66deg,#eaedff 24.3%,#ffeaf4 86.64%);
            "
          >
            <div style="float: right; margin-right: 200px; margin-top: -50px">
              <v-img
                min-width="300"
                min-height="300"
                src="https://cdn.jsdelivr.net/gh/qiananran/myImage/onlinestudy/Saly-1.png"
              >
              </v-img>
            </div>
            <div style="margin-top: 141px; margin-left: 100px">
              <v-card-title>
                <h1
                  style="
                    font-family: Montserrat;
                    font-style: normal;
                    font-weight: bold;
                    letter-spacing: -1px;

                    color: #001a49;
                  "
                >
                  Learn no-code <br /><br />
                  <span style="color: #1028ff">tools today.</span>
                </h1>
              </v-card-title>
              <v-card-text
                style="
                  width: 500px;
                  margin-top: 30px;
                  font-family: Mulish;
                  font-style: normal;
                  font-weight: normal;
                  font-size: 18px;
                  line-height: 30px;
                  /* or 150% */

                  color: #4f596a;
                "
                >Create beautiful webflow sites with flowbase. Clone for free
                and get started building a site today.</v-card-text
              >
              <v-btn
                style="
                  color: white;
                  background: linear-gradient(35deg,#1028ff 15.75%,#ff067e 84.63%);
                  border-radius: 80px;
                  margin-left: 20px;
                  margin-top: 30px;
                "
                color="#4461F2"
                height="45px"
                width="150px"
                >快 速 开 始</v-btn
              >

              <div class="gorup">
                <div class="gorup1">
                  <v-avatar>
                    <img
                      class="myavatar"
                      src="https://cdn.vuetifyjs.com/images/john.jpg"
                      alt="John"
                    />
                  </v-avatar>
                </div>
                <div class="gorup1">
                  <v-avatar>
                    <img
                      class="myavatar"
                      src="https://images.pexels.com/photos/8794308/pexels-photo-8794308.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
                      alt="John"
                    />
                  </v-avatar>
                </div>
                <div class="gorup1">
                  <v-avatar>
                    <img
                      class="myavatar"
                      src="https://images.pexels.com/photos/10819697/pexels-photo-10819697.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
                      alt="John"
                    />
                  </v-avatar>
                </div>
                <div class="gorup1" style="margin-left: -20px">
                  <v-card-text
                    style="
                      width: 300px;
                      font-family: Mulish;
                      font-style: normal;
                      font-weight: normal;
                      font-size: 16px;
                      line-height: 20px;
                    "
                    ><span style="color: #001a49"
                      >Join over 4,000+ students</span
                    ></v-card-text
                  >
                  <v-avatar>
                    <span style=""></span>
                  </v-avatar>
                </div>
              </div>
            </div>

            <div
              style="
                float: right;
                margin-right: 150px;
                margin-top: -370px;
                width: 550px;
                height: 550px;
              "
            >
              <v-img
                style=""
                src="https://cdn.jsdelivr.net/gh/qiananran/myImage/onlinestudy/Component2.png"
              >
              </v-img>
            </div>
          </v-card>
          <v-card
            min-width="620"
            min-height="350"
            style="
              background: #001a49;
              box-shadow: 0px 32px 44px #818a8c;
              border-radius: 20px 0px 0px 20px;
              margin-left: -200px;
              padding: 0px 90px;
              display: flex;
              justify-content: center;
              align-items: center;
            "
          >
            <v-avatar color="white" size="62">
              <v-icon style="width: 32px; height: 32px">mdi-play</v-icon>
            </v-avatar>
          </v-card>
        </div>
      </div>

      <div>
        <div
          style="
            width: 228px;
            height: 228px;
            margin-top: 127px;
            margin-left: -40px;
          "
        >
          <v-img src="https://cdn.jsdelivr.net/gh/qiananran/myImage/onlinestudy/SideShape.svg"></v-img>
        </div>

        <div style="margin-top: -240px; float: inline-start">
          <v-container fluid>
            <v-card
              elevation="0"
              min-height="120"
              style="
                margin-left: 100px;
                margin-right: 100px;
                background: url('https://cdn.jsdelivr.net/gh/qiananran/myImage/img/awj42-pxaqg.png');
                background-position: center center;
                background-size: cover;
                border-radius: 15px;
              "
            >
              <div
                style="
                  display: flex;
                  justify-content: space-between;
                  align-items: center;
                  padding: 20px;
                  margin-left: 40px;
                  margin-right: 40px;
                "
              >
                <div style="text-align: center">
                  <span class="my_date">12,201</span><br />
                  <span>happy students</span>
                </div>
                <div style="text-align: center">
                  <span class="my_date">3,291</span><br />
                  <span>lectures</span>
                </div>
                <div style="text-align: center">
                  <span class="my_date" style="color: white">1,291</span><br />
                  <span style="color: white; margin-top: 8px"
                    >5 star reviews</span
                  >
                </div>
              </div>
            </v-card>
          </v-container>
        </div>
      </div>

      <div style="margin-top: 80px">
        <div>
          <v-row>
            <v-col cols="12">
              <div
                style="
                  display: flex;
                  justify-content: center;
                  align-items: center;
                "
              >
                <div
                  style="
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                  "
                >
                  <div style="align-items: center; padding: 40px">
                    <v-row>
                      <v-col cols="12">
                        <div
                          style="
                            display: flex;
                            justify-content: center;
                            align-items: center;
                            flex-direction: column;
                          "
                        >
                          <div
                            class="my_text"
                            style="
                              font-size: 32px;
                              margin-top: 40px;
                              text-align: center;
                            "
                          >
                            <span style="color: #2f327d"
                              >我们
                              <span style="color: #f48c06; margin-left: 2px">
                                特性</span
                              ></span
                            >
                            <br />
                            <p style="font-size: 24px">
                              这个非常特别的功能，可以使学习活动更加高效
                            </p>
                          </div>
                          <div
                            style="
                              display: flex;
                              flex-direction: column;
                              margin-top: 50px;
                            "
                          >
                            <div>
                              <div style="display: flex">
                                <v-col cols="7">
                                  <v-img
                                    width="650"
                                    src="https://cdn.jsdelivr.net/gh/qiananran/myImage/img/Group83.png"
                                  ></v-img>
                                </v-col>
                                <v-col cols="5">
                                  <p
                                    class="my_text"
                                    style="
                                      color: #2f327d;
                                      font-weight: bold;
                                      width: 400px;
                                    "
                                  >
                                    A
                                    <span style="color: #f48c06"
                                      >user interface</span
                                    >
                                    designed for the classroom
                                  </p>
                                  <div
                                    style="
                                      display: flex;
                                      justify-content: center;
                                      align-items: center;
                                      margin-top: 40px;
                                    "
                                  >
                                    <v-btn
                                      class="mx-2"
                                      fab
                                      dark
                                      color="white"
                                      small
                                    >
                                      <v-icon color="primary">
                                        mdi-account-heart
                                      </v-icon>
                                    </v-btn>
                                    <span
                                      class="ml-4"
                                      style="
                                        width: 400px;
                                        line-height: 180%;
                                        letter-spacing: 0.02em;
                                        color: #696984;
                                      "
                                      >Teachers don’t get lost in the grid view
                                      and have a dedicated Podium space.
                                    </span>
                                  </div>
                                  <div
                                    style="
                                      display: flex;
                                      justify-content: center;
                                      align-items: center;
                                      margin-top: 40px;
                                    "
                                  >
                                    <v-btn
                                      class="mx-2"
                                      fab
                                      dark
                                      color="white"
                                      small
                                    >
                                      <v-icon color="success">
                                        mdi-coffee-maker
                                      </v-icon>
                                    </v-btn>
                                    <span
                                      class="ml-4"
                                      style="
                                        width: 400px;
                                        line-height: 180%;
                                        letter-spacing: 0.02em;
                                        color: #696984;
                                      "
                                      >Teachers don’t get lost in the grid view
                                      and have a dedicated Podium space.
                                    </span>
                                  </div>
                                  <div
                                    style="
                                      display: flex;
                                      justify-content: center;
                                      align-items: center;
                                      margin-top: 40px;
                                    "
                                  >
                                    <v-btn
                                      class="mx-2"
                                      fab
                                      dark
                                      color="white"
                                      small
                                    >
                                      <v-icon color="red">
                                        mdi-cards-heart
                                      </v-icon>
                                    </v-btn>
                                    <span
                                      class="ml-4"
                                      style="
                                        width: 400px;
                                        line-height: 180%;
                                        letter-spacing: 0.02em;
                                        color: #696984;
                                      "
                                      >Teachers don’t get lost in the grid view
                                      and have a dedicated Podium space.
                                    </span>
                                  </div>
                                </v-col>
                              </div>
                            </div>
                            <div style="margin-top: 120px">
                              <div style="display: flex">
                                <v-col
                                  cols="5"
                                  style="
                                    display: flex;
                                    flex-direction: column;
                                    align-items: center;
                                    justify-content: center;
                                  "
                                >
                                  <div>
                                    <div style="width: 300px">
                                      <p
                                        class="my_text"
                                        style="
                                          color: #2f327d;
                                          font-weight: bold;
                                        "
                                      >
                                        <span style="color: #f48c06"
                                          >Tools</span
                                        >
                                        For Teachers And Learners
                                      </p>
                                    </div>

                                    <div style="width: 400px">
                                      <span
                                        style="
                                          line-height: 180%;
                                          letter-spacing: 0.02em;
                                          color: #696984;
                                        "
                                        >Class has a dynamic set of teaching
                                        tools built to be deployed and used
                                        during class.Teachers can handout
                                        assignments in real-time for students to
                                        complete and submit.</span
                                      >
                                    </div>
                                  </div>
                                </v-col>
                                <v-col cols="7" class="ml-15">
                                  <v-img
                                    width="600"
                                    height="610"
                                    src="https://cdn.jsdelivr.net/gh/qiananran/myImage/img/Group122.png"
                                  ></v-img>
                                </v-col>
                              </div>
                            </div>
                            <div style="margin-top: 120px">
                              <div style="display: flex">
                                <v-col cols="7" class="ml-15">
                                  <div style="width: 600px; height: 400px">
                                    <v-img
                                      src="https://cdn.jsdelivr.net/gh/qiananran/myImage/img/Group92.png"
                                    ></v-img>
                                  </div>
                                </v-col>
                                <v-col
                                  cols="5"
                                  style="
                                    display: flex;
                                    flex-direction: column;
                                    align-items: center;
                                    justify-content: center;
                                  "
                                >
                                  <div>
                                    <div style="width: 300px">
                                      <p
                                        class="my_text"
                                        style="
                                          color: #2f327d;
                                          font-weight: bold;
                                        "
                                      >
                                        <span style="color: #f48c06"
                                          >Quizzes,</span
                                        >
                                        Assessments, Tests
                                      </p>
                                    </div>

                                    <div style="width: 400px">
                                      <span
                                        style="
                                          line-height: 180%;
                                          letter-spacing: 0.02em;
                                          color: #696984;
                                        "
                                        >Easily launch live assignments,
                                        quizzes, and tests.Student results are
                                        automatically entered in the online
                                        gradebook.</span
                                      >
                                    </div>
                                  </div>
                                </v-col>
                              </div>
                            </div>
                            <div style="margin-top: 220px">
                              <div style="display: flex">
                                <v-col
                                  cols="5"
                                  style="
                                    display: flex;
                                    flex-direction: column;
                                    align-items: center;
                                    justify-content: center;
                                  "
                                >
                                  <div>
                                    <div style="width: 300px">
                                      <p
                                        class="my_text"
                                        style="
                                          color: #2f327d;
                                          font-weight: bold;
                                        "
                                      >
                                        <span style="color: #f48c06"
                                          >Class Management</span
                                        >
                                        Tools for Educators
                                      </p>
                                    </div>

                                    <div style="width: 400px">
                                      <span
                                        style="
                                          line-height: 180%;
                                          letter-spacing: 0.02em;
                                          color: #696984;
                                        "
                                        >Class provides tools to help run and
                                        manage the class such as Class Roster,
                                        Attendance, and more. With the
                                        Gradebook, teachers can review and grade
                                        tests and quizzes in real-time.</span
                                      >
                                    </div>
                                  </div>
                                </v-col>
                                <v-col cols="7" class="ml-15">
                                  <div style="width: 650px; height: 400px">
                                    <v-img
                                      src="https://cdn.jsdelivr.net/gh/qiananran/myImage/img/Group124.png"
                                    ></v-img>
                                  </div>
                                </v-col>
                              </div>
                            </div>
                            <div style="margin-top: 220px">
                              <div style="display: flex">
                                <v-col cols="7">
                                  <div style="width: 650px; height: 450px">
                                    <v-img
                                      src="https://cdn.jsdelivr.net/gh/qiananran/myImage/img/Group106.png"
                                    ></v-img>
                                  </div>
                                </v-col>
                                <v-col
                                  cols="5"
                                  style="
                                    display: flex;
                                    flex-direction: column;
                                    align-items: center;
                                    justify-content: center;
                                  "
                                >
                                  <div>
                                    <div style="width: 300px">
                                      <p
                                        class="my_text"
                                        style="
                                          color: #2f327d;
                                          font-weight: bold;
                                        "
                                      >
                                        One-on-One
                                        <span style="color: #f48c06"
                                          >Discussions</span
                                        >
                                      </p>
                                    </div>

                                    <div style="width: 400px">
                                      <span
                                        style="
                                          line-height: 180%;
                                          letter-spacing: 0.02em;
                                          color: #696984;
                                        "
                                        >Teachers and teacher assistants can
                                        talk with students privately without
                                        leaving the Zoom environment.</span
                                      >
                                    </div>
                                  </div>
                                </v-col>
                              </div>
                            </div>
                          </div>
                        </div>
                      </v-col>
                    </v-row>
                  </div>
                </div>
              </div>
            </v-col>
          </v-row>
        </div>
      </div>

      <div>
        <v-img
          width="340"
          height="340"
          src="https://cdn.jsdelivr.net/gh/qiananran/myImage/onlinestudy/Saly-43.png"
        ></v-img>
      </div>

      <div
        style="
          width: 100%;
          height: 620px;
          margin-top: -200px;
          background: linear-gradient(86.22deg,#00bdde -60.63%,#00bdde -60.61%,#4f62ee 34.92%,#9f06ff 99.95%);
        "
      >
        <div>
          <v-row>
            <v-col cols="12" style="margin-top: 160px">
              <div
                style="
                  display: flex;
                  justify-content: center;
                  align-items: center;
                "
              >
                <div style="margin-right: 180px">
                  <div
                    style="
                      display: flex;
                      justify-content: left;
                      align-items: center;
                    "
                  >
                    <div
                      style="
                        width: 80px;
                        height: 0px;
                        border: 1px solid #525596;
                      "
                    ></div>
                    <span style="margin-left: 20px">INTEGRATIONS</span>
                  </div>
                  <div style="margin-top: 20px">
                    <p style="margin-top: 20px; color: #ffff; font-size: 32px">
                      他们怎么说？
                    </p>
                    <p
                      style="
                        margin-top: 20px;
                        width: 550px;
                        font-size: 20px;
                        line-height: 150%;
                        color: white;
                      "
                    >
                      Schoology has every tool your , student information
                      systems (SIS), and education platforms.
                    </p>
                    <p style="color:white">
                      classroom needs and comes pre-integrated with more than
                      200+ tools
                    </p>
                    <p style="color:white">
                      classroom needs and comes pre-integrated with more than
                      200+ tools
                    </p>
                  </div>
                  <div style="margin-top: 40px">
                    <v-btn
                      width="240px"
                      height="50px"
                      style="
                        font-size: 18px;
                        background: linear-gradient(35deg,#aa32c9 15.75%,#ca6c9a 84.63%);
                      "
                      outlined
                      class="rounded-pill"
                    >
                      <span style="color: white">See All Integrations</span>
                    </v-btn>
                  </div>
                  <br />
                  <br />
                </div>
                <div>
                  <div style="display: flex">
                    <div
                      style="height: 300px; width: 300px; margin-top: -105px"
                    >
                      <v-img
                        src="https://cdn.jsdelivr.net/gh/qiananran/myImage/img/MaskGroup.png"
                      ></v-img>
                    </div>

                    <div style="margin-left: -30px; height: 60px">
                      <v-btn
                        class="mx-2"
                        fab
                        dark
                        large
                        color="white"
                        height="60px"
                      >
                        <v-icon color="#1EA4CE"> mdi-chevron-right </v-icon>
                      </v-btn>
                    </div>
                  </div>
                  <div style="margin-left: 50px; margin-top: -50px">
                    <v-card
                      width="450px"
                      height="230px"
                      class=""
                      style="
                        background: rgba(255, 255, 255, 0.8);
                        box-shadow: 2px 4px 60px rgba(41, 44, 124, 0.1);
                        border-radius: 20px;
                        padding: 20px;
                        backdrop-filter: blur(10px);
                      "
                    >
                      <v-card-text>
                        "Thank you so much for your help. It's exactly what I've
                        been looking for. You won't regret it. It really saves
                        me time and effort. Skilline is exactly what our
                        business has been lacking."
                      </v-card-text>
                      <v-card-text>Gloria Rose</v-card-text>
                      <v-rating
                        :value="4"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                      ></v-rating>
                    </v-card>
                  </div>
                  <br />
                </div>
              </div>
            </v-col>
          </v-row>
        </div>
      </div>

      <div style="margin-top: 30px">
        <div>
          <v-container>
            <div>
              <v-row>
                <v-col cols="12" style="text-align: center">
                  <span
                    style="
                      font-family: Montserrat;
                      font-style: normal;
                      font-weight: bold;
                      font-size: 46px;
                      line-height: 56px;
                      /* identical to box height, or 122% */

                      text-align: center;

                      color: #001a49;
                    "
                    >常见问题</span
                  >
                </v-col>
                <v-col cols="12">
                  <div id="myapp">
                    <div class="list" v-for="(l, i) in lists" :key="i">
                      <div class="title" @click="toggle($event)">
                        {{ l.title }}
                      </div>
                      <ul class="item">
                        <li v-for="(item, index) in l.items" :key="index">
                          {{ item }}
                        </li>
                      </ul>
                    </div>
                  </div>
                </v-col>
              </v-row>
            </div>
          </v-container>
        </div>
      </div>

      <div>
        <v-container>
          <v-row>
            <v-col
              cols="12"
              style="
                display: flex;
                justify-content: center;
                align-items: center;
                margin-top: 60px;
              "
            >
              <div
                style="
                  width: 402px;
                  background: #fff4e9;
                  mix-blend-mode: normal;

                  border-radius: 33px;
                  height: 33px;
                  text-align: center;
                  padding: 5px;
                "
              >
                <span
                  style="
                    padding: 10px;
                    color: #ab24fb;
                    letter-spacing: 2.57143px;
                    text-transform: uppercase;
                  "
                >
                  Learn something</span
                >
              </div>

              <br />
            </v-col>
            <v-col
              cols="12"
              style="
                display: flex;
                justify-content: center;
                align-items: center;
                margin-top: 60px;
              "
            >
              <div
                style="
                  text-align: center;
                  font-family: Montserrat;
                  font-style: normal;
                  font-weight: bold;
                  font-size: 46px;
                  line-height: 56px;
                  color: #001a49;
                "
              >
                <span>了解完了？</span><br />
                <p style="margin-top: 15px">那就让我们开始吧!</p>
              </div>
            </v-col>
            <v-col
              style="
                display: flex;
                justify-content: center;
                align-items: center;
              "
            >
              <v-btn
                style="
                  color: white;
                  background: linear-gradient(35deg,#1028ff 15.75%,#ff067e 84.63%);
                  border-radius: 80px;
                  margin-left: 20px;
                "
                color="#4461F2"
                height="60px"
                width="240px"
                ><span style="font-size: 24px">快速开始</span></v-btn
              >
            </v-col>
          </v-row>
        </v-container>
      </div>
    </v-main>
    <div style="margin-top: 100px"></div>
    <Footer />
  </div>
</template>

<script>
import Footer from "../components/Footer.vue";
export default {
  name: "Home",

  components: { Footer },
  data() {
    return {
      show: false,
      btnText: ["Home", "Careers", "Blog", "About Us"],
      menus: [
        { title: "Home", route: "home" },
        { title: "About us", route: "about-us" },
        { title: "Price", route: "price" },
        { title: "Project", route: "project" },
        { title: "Gallery", route: "galley" },
        { title: "Contact", route: "contact" },
      ],
      lists: [
        { title: "如何使用？", items: ["打开网站，直接访问即可"] },
        { title: "费用如何？", items: ["适当收费"] },
        { title: "怎么留言？", items: ["打开留言板"] },
      ],
    };
  },

  methods: {
    toggle: function (ev) {
      var $title = $(ev.target);
      $title.parents("#myapp").find(".item").hide();
      $title.next().show(1000);
    },
  },
};
</script>

<style scoped>
ul {
  list-style: none;
}

li {
  padding-left: 10px;
  line-height: 2;
}

li:hover {
  background-color: #eee;
}

.list {
  padding: 0 50px;
  margin-top: 20px;
}

.list .title {
  border-radius: 20px 20px 0 0;
  border: 1px solid rgb(159, 27, 211);
  padding: 20px 15px;
  cursor: pointer;
  -webkit-user-select: none;
  user-select: none;
  font-size: 18px;
  font-weight: bold;
}

.list .item {
  border: 1px solid rgb(159, 27, 211);
  border-radius: 0 0 15px 15px;
}

.list:not(:nth-of-type(1)) .item {
  display: none;
}
.v-btn {
  text-transform: none;
}
.my_bar {
  width: 1340px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.my_bartext{
  font-family: Poppins;
  font-style: normal;
  font-weight: 500;
  line-height: 160%;
  font-size: 18px;
  /* identical to box height, or 45px */
  letter-spacing: 0.02em;
 
}

.my_text {
  font-family: Poppins;
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 160%;
  /* identical to box height, or 45px */
  letter-spacing: 0.02em;
  color: #696984;
}
.btn_login {
  box-shadow: 0px 20px 24px rgba(0, 0, 0, 0.03);
  border-radius: 80px;
  margin-left: 20px;
  margin-right: 5px;
}
.my_sub {
  font-family: Poppins;
  font-style: normal;
  font-weight: bold;
  font-size: 32px;
}
.my_subtitle {
  margin-top: 25px;
  width: 500px;
  height: 76px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 160%;
  /* or 38px */
  color: #464646;
}

.gorup {
  display: flex;
  flex-wrap: wrap;
  width: 400px;
  justify-content: left;
  margin-top: 50px;
  margin-left: 15px;
}
.gorup > .gorup1 {
  margin-bottom: 10px;
  margin-right: 1px;
  width: 30px;
  height: 50px;
  text-align: center;
  line-height: 50px;
  color: #fff;
}
.gorup > .gorup1 > .myavatar {
  display: inline-block;
  width: 50px;
  height: 50px;
  background: gainsboro;
  border-radius: 50%;
  border: 1px solid red;
}

.my_date {
  font-family: Montserrat;
  font-style: normal;
  font-weight: bold;
  font-size: 40px;
  line-height: 50px;
  /* identical to box height, or 125% */

  text-align: center;

  color: #001a49;
}
</style>