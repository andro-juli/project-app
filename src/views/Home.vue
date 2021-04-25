<template>
  <div class="home">
    <Navbar />
    <section id="hero">
      <div class="container">
        <div class="row">
          <div class="">
            <div class="section-body">
              <h6>PLAN YOUR LIFE</h6>
              <h1>
                Increase your <span style="font-weight:500;">productivity</span>
              </h1>
              <p>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu <br />
                atqui laudem an, insolens gubergren similique est cu. Et vel
                modus <br />
                congue vituperata.
              </p>
              <div>
                <img src="../assets/play button.svg" class="play-btn" alt="" />
              </div>
            </div>
            <div>
              <img src="../assets/stats.svg" class="stats-icon" alt="" />
            </div>

            <img src="../assets/clouds.svg" class="hero-image1" alt="" />
            <img src="../assets/chart.svg" class="hero-image2" alt="" />
          </div>
        </div>
      </div>
    </section>
    <section class="section-one">
      <div>
        <img src="../assets/Bitbucket.svg" class="section1-icon" alt="" />
      </div>
      <div><img src="../assets/watch.svg" class="section1-icon" alt="" /></div>
      <div>
        <img src="../assets/facebook.svg" class="section1-icon" alt="" />
      </div>
      <div>
        <img src="../assets/Atlassian.svg" class="section1-icon" alt="" />
      </div>
      <div><img src="../assets/Audi.svg" class="section1-icon" alt="" /></div>
    </section>
    <section class="section-two">
      <div class="section-two-main">
        <div class="left-div">
          <h6>DESKTOP AND MOBILE APP</h6>
          <h1>Plan <span class="span-text">and</span> manage</h1>
          <p>
            Brute laoreet efficiendi id his, ea illum nonumes luptatum <br />
            pro. Usu atqui laudem an, insolens gubergren similique <br />
            est cu. Et vel modus congue vituperata. Solum patrioque <br />
            no sea. Mea ex malis mollis oporteat. Eum an expetenda <br />
            consequat.
          </p>
          <div class="">
            <p>
              <button class="btn1">
                View video <img src="../assets/Polygon.svg" alt="" />
              </button>
              <span><button class="btn2">See features</button></span>
            </p>
          </div>
        </div>
        <div class="right-div">
          <img src="../assets/illustration.png" alt="" />
        </div>
      </div>
    </section>
    <section class="section-three">
      <div class="">
        <img src="../assets/cloud3.svg" class="" alt="" />
      </div>
      <div class="section-three-body">
        <h6 class="section-three-head">ABOUT US</h6>
        <h3>Read about our app</h3>
        <div class="about-us">
          <div class="col-sm-2">
            <div class="circle">
              <div><img src="../assets/overview.svg" alt="" /></div>
            </div>
            <h6>Overview</h6>
            <p>
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
            </p>
          </div>
          <div class="col-sm-2">
            <div class="circle">
              <div><img src="../assets/files.svg" alt="" /></div>
            </div>
            <h6>Files</h6>
            <p>
              No vim nulla vitae intellegat. Ei enim error ius, solet atomorum
              conceptam ex has.
            </p>
          </div>
          <div class="col-sm-2">
            <div class="circle">
              <div><img src="../assets/chats.svg" alt="" /></div>
            </div>
            <h6>Meeting chats</h6>
            <p>Vim ne tacimates neglegentur. Erat diceret omittam at est.</p>
          </div>
          <div class="col-sm-2">
            <div class="circle">
              <div><img src="../assets/save.svg" alt="" /></div>
            </div>
            <h6>Save events</h6>
            <p>Nisl idque mel ea, nominati voluptatum.</p>
          </div>
        </div>
        <div class="section-three-btn-div">
          <p>
            <button class="red-btn">Read more</button> <span>OR</span>
            <span><button class="btn">Get Started</button></span>
          </p>
        </div>
      </div>
      <div>
        <img src="../assets/cloud4.svg" alt="" />
      </div>
    </section>
    <section class="section-four">
      <div class="div-one">
        <div class="col-sm-5">
          <div class="icon-card">
            <img src="../assets/tracker.svg" alt="" />
          </div>
          <p class="number-card">89%</p>
          <p class="text-card">
            Customers who have increased their productivity
          </p>
        </div>
      </div>
      <div class="div-two">
        <div class="col-sm-5">
          <div><img src="../assets/people.svg" alt="" /></div>
          <p class="number-card2">3123</p>
          <p class="text-card2">Users who have used our application</p>
        </div>
      </div>
    </section>
    <section class="section-five">
      <h6>OUR RESOURCES</h6>
      <h3>Start reading our blog</h3>
      <div class="blog-div">
        <div class="left-arrow">
          <img src="../assets/leftarrow.svg" alt="" />
        </div>
        <carousel
          :per-page="1"
          :navigate-to="someLocalProperty"
          :mouse-drag="true"
        >
          <slide>
            <div class="blog-post-div">
              <div class="blog-image-div">
                <img src="../assets/blogpost.png" alt="" class="blog-image" />
              </div>
              <div class="blog-content">
                <h4>How to start planning</h4>
                <p class="blog-text">
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti. Natum petentium principes mei ea. Tota everti
                  periculis vis ei, quas tibique pro at, eos ut decore ...
                </p>
                <p>
                  <button class="readnow-btn">Read now</button>
                  <span class="bookmark">Add to your bookmarks</span>
                </p>
              </div>
            </div>
          </slide>
          <slide>
            <div class="blog-post-div">
              <div class="blog-image-div">
                <img src="../assets/blogpost.png" alt="" class="blog-image" />
              </div>
              <div class="blog-content">
                <h4>How to start planning</h4>
                <p class="blog-text">
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti. Natum petentium principes mei ea. Tota everti
                  periculis vis ei, quas tibique pro at, eos ut decore ...
                </p>
                <p>
                  <button class="readnow-btn">Read now</button>
                  <span class="bookmark">Add to your bookmarks</span>
                </p>
              </div>
            </div>
          </slide>
          <slide>
            <div class="blog-post-div">
              <div class="blog-image-div">
                <img src="../assets/blogpost.png" alt="" class="blog-image" />
              </div>
              <div class="blog-content">
                <h4>How to start planning</h4>
                <p class="blog-text">
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti. Natum petentium principes mei ea. Tota everti
                  periculis vis ei, quas tibique pro at, eos ut decore ...
                </p>
                <p>
                  <button class="readnow-btn">Read now</button>
                  <span class="bookmark">Add to your bookmarks</span>
                </p>
              </div>
            </div>
          </slide>
        </carousel>
        <div class="right-arrow">
          <img src="../assets/rightarrow.svg" alt="" />
        </div>
      </div>
    </section>
    <section class="section-six">
      <div class="testimonials">
        <div class="left-div1">
          <div class="lefty">
            <h6>TESTIMONIALS</h6>
            <h3>Customers's quotes</h3>
            <p>
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
              Usu atqui laudem an.
            </p>
          </div>
        </div>
        <div class="right-div1">
          <div>
            <carousel
              :per-page="1"
              :navigate-to="someLocalProperty"
              :mouse-drag="false"
            >
              <slide>
                <div class="qoute-div">
                  <p>
                    Quidam vocibus eum ne, erat consectetuer <br />
                    voluptatibus ut nam. Eu usu vidit tractatos, <br />
                    vero tractatos ius an, in mel diceret persecuti.
                  </p>
                </div>
              </slide>
              <slide>
                <div class="qoute-div">
                  <p>
                    Quidam vocibus eum ne, erat consectetuer voluptatibus ut
                    nam. Eu usu vidit tractatos, vero tractatos ius an, in mel
                    diceret persecuti.
                  </p>
                </div>
              </slide>
              <slide>
                <div class="qoute-div">
                  <p>
                    Quidam vocibus eum ne, erat consectetuer voluptatibus ut
                    nam. Eu usu vidit tractatos, vero tractatos ius an, in mel
                    diceret persecuti.
                  </p>
                </div>
              </slide>
              <slide>
                <div class="qoute-div">
                  <p>
                    Quidam vocibus eum ne, erat consectetuer voluptatibus ut
                    nam. Eu usu vidit tractatos, vero tractatos ius an, in mel
                    diceret persecuti.
                  </p>
                </div>
              </slide>
              <slide>
                <div class="qoute-div">
                  <p>
                    Quidam vocibus eum ne, erat consectetuer voluptatibus ut
                    nam. Eu usu vidit tractatos, vero tractatos ius an, in mel
                    diceret persecuti.
                  </p>
                </div>
              </slide>
              <slide>
                <div class="qoute-div">
                  <p>
                    Quidam vocibus eum ne, erat consectetuer voluptatibus ut
                    nam. Eu usu vidit tractatos, vero tractatos ius an, in mel
                    diceret persecuti.
                  </p>
                </div>
              </slide>
            </carousel>
            <div class="pic-div">
              <img src="../assets/picture.png" class="picture" alt="" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section-seven">
      <div class="section-seven-main">
        <h6>CUSTOMER HELP</h6>
        <h3>Frequently asked questions</h3>
        <div>
          <p>
            <span><img src="../assets/arr.svg" alt=""/></span> Reque insolens in
            vel?
          </p>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/arr.svg" alt=""/></span> Vis rebum error
            graecis ea, id sit postea accusamus?
          </p>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/arr.svg" alt=""/></span> Lorem repudiandae
            ne nec?
          </p>
          <div class="faq-drop-down">
            <p>
              Quidam vocibus eum ne, erat consectetuer voluptatibus ut <br />
              nam. Eu usu vidit tractatos, vero tractatos ius an, in mel <br />
              diceret persecuti.
              <span><button class="FAQ-btn">Go to documentation</button></span>
            </p>
          </div>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/arr.svg" alt=""/></span> Ad dicit numquam
            vel. Et eos iudico feugait percipitur?
          </p>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/arr.svg" alt=""/></span> Sea no dico
            percipitur. Fierent constituam definitiones id eum?
          </p>
          <div class="line"></div>
        </div>
      </div>
    </section>
    <section class="section-eight">
      <div class="blue-cloud">
        <div>
          <img src="../assets/bluecloud1.svg" class="" alt="" />
        </div>
        <div class="blue-cloud-text">
          <h6>PLAN YOUR LIFE</h6>
          <h2>Get <span style="font-weight: 500;">started</span> now</h2>
          <p>
            Brute laoreet efficiendi id his, ea illum nonumes luptatum pro. Usu
            atqui laudem an, insolens gubergren similique est cu. Et vel modus
            congue vituperata.
          </p>
          <div class="blue-cloud-btn-div">
            <button class="view-pricing-btn">View pricing</button>
            <button class="docu-btn">Read documentation</button>
          </div>
        </div>
        <div class="cloud2">
          <img src="../assets/bluecloud2.svg" class="blue-cloud2" alt="" />
        </div>
      </div>
    </section>
    <section class="section-nine">
      <div class="section-nine-main">
        <div class="left-div3">
          <h4>Sign up for newsletter</h4>
          <p>
            Cu qui soleat partiendo urbanitas. Eum aperiri indoctum eu, homero
            alterum.
          </p>
        </div>
        <div class="right-div3">
          <p>
            <input
              class="input-email"
              type="text"
              placeholder="Email address"
            /><button class="save-btn">
              Save me
            </button>
          </p>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
import { Carousel, Slide } from "vue-carousel";

export default {
  name: "Home",

  components: {
    Carousel,
    Slide,
    Navbar,
    Footer,
  },
};
</script>

<style scoped>
.home {
  background: #ffffff;
}

#hero {
  background: linear-gradient(180deg, #f4f7ff 0%, #f1f5ff 100%);
  width: 100%;
  height: 570px;
}
.hero-image1 {
  width: 100%;
  height: 570px;
  position: relative;
  top: 50px;
  right: 110px;
}
.hero-image2 {
  width: 100%;
  height: 570px;
  position: absolute;
  top: 190px;
  left: 0;
}

.section-body {
  text-align: center;
  margin-top: 90px;
  position: absolute;
  width: 50%;
  left: 325px;
}
.section-body h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
}

.section-body h1 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 300;
  font-size: 48px;
  line-height: 60px;
  color: #3d4f9f;
}
.section-body p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 29px;
  text-align: center;
  letter-spacing: 0.03em;
  color: #8d96bd;
}

.stats-icon {
  position: absolute;
  top: 512px;
  left: 392px;
}
.section-one {
  display: flex;
  justify-content: space-around;
  width: 100%;
  height: 145px;
  background: #ffffff;
  align-items: center;
  padding-right: 80px;
  padding-left: 80px;
}
.section1-icon {
  width: 6rem;
  height: 2.9rem;
}
.section-two {
  background: #f5f8ff;
  width: 100%;
  height: 750px;
}
.section-two-main {
  display: flex;
  width: 100%;
}
.left-div {
  width: 50%;
  margin-top: 12rem;
  padding-left: 10rem;
}
.right-div {
  width: 50%;
  margin-top: 8rem;
}
.left-div h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
  padding-bottom: 10px;
}
.left-div h1 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 45px;
  color: #3d4f9f;
  padding-top: 10px;
}
.left-div p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 25px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  padding-top: 10px;
}
.span-text {
  color: #5f77e2;
}
.right-div {
  align-items: center;
  width: 100%;
  display: flex;
  justify-items: center;
}
.btn1 {
  width: 30%;
  height: 43px;
  background: #4c85ff;
  box-shadow: 0px 5px 15px rgba(188, 199, 255, 0.75);
  border-radius: 2px;
  color: #ffffff;
}
.btn2 {
  width: 30%;
  height: 43px;
  background: #f5f8ff;
  box-shadow: 0px 5px 15px rgba(188, 199, 255, 0.75);
  border-radius: 2px;
  color: #bec0c5;
}
.section-three-body {
  margin-top: 4rem;
}
.section-three {
  width: 100%;
  height: 750px;
  background: #ffffff;
  display: flex;
}

.circle {
  width: 69px;
  height: 69px;
  background: #f1f5ff;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  padding-top: 21px;
  margin: 20px;
}
.about-us {
  display: flex;
  justify-content: center;
}
.section-three {
  padding-top: 3rem;
}
.section-three-head {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
  text-align: center;
  padding: 20px;
}
.section-three h3 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 30px;
  text-align: center;
  color: #3d4f9f;
  padding: 20px;
}
.about-us h6 {
  font-family: Open Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 25px;
  text-align: center;
  color: #4074f8;
}
.about-us p {
  font-family: Open Sans;
  font-style: normal;
  font-weight: 500;
  font-size: 11px;
  line-height: 19px;
  text-align: center;
  color: #adb3cb;
}
.btn {
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #3a79ff;
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  margin-left: 30px;
}
.red-btn {
  width: 113px;
  height: 43px;
  background: #ffd7d7;
  border-radius: 2px;
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #d43f3f;
  border: none;
  margin-right: 30px;
}
.section-three-btn-div {
  display: flex;
  justify-content: center;
  margin-top: 8rem;
}

.section-four {
  display: flex;
}
.text-card {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 23px;
  letter-spacing: 0.03em;
  text-indent: 55px;
}

.text-card2 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 23px;
  letter-spacing: 0.03em;
}
.div-one {
  width: 50%;
  height: 342px;
  background: linear-gradient(229.32deg, #6888ff 12.77%, #5e80ff 73.11%);
  color: #ffffff;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.div-two {
  width: 50%;
  height: 342px;
  background: linear-gradient(101.48deg, #e9efff 41.56%, #e0e9ff 81.53%);
  color: #5e80ff;
  display: flex;
  align-items: center;
}
.number-card {
  font-family: Quicksand;
  font-style: normal;
  font-weight: normal;
  font-size: 48px;
  line-height: 83px;
  letter-spacing: 0.03em;
  text-align: right;
}
.number-card2 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: normal;
  font-size: 48px;
  line-height: 83px;
  letter-spacing: 0.03em;
}
.icon-card {
  display: flex;
  justify-content: flex-end;
}

.section-five {
  width: 100%;
  height: 820px;
  background: #f5f8ff;
  padding-top: 8rem;
}
.blog-post-div {
  width: 70%;
  height: 350px;
  background: #ffffff;
  border: 1px solid #d8e3fe;
  box-shadow: 0px 15px 50px #eff4ff;
  display: flex;
  justify-content: center;
  margin: auto;
}
.section-five h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
  padding: 20px;
  text-align: center;
}
.section-five h3 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 30px;
  text-align: center;
  color: #3d4f9f;
  text-align: center;
  padding: 20px;
}
.section-five h4 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: normal;
  font-size: 32px;
  line-height: 40px;
  color: #3d4f9f;
}
.blog-text {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.03em;
  color: #8d96bd;
}
.readnow-btn {
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #3a79ff;
  border: none;
}
.bookmark {
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #a6b6da;
  margin-left: 10px;
}
.blog-image-div {
  width: 45%;
}
.blog-content {
  width: 45%;
  margin-top: 3rem;
}
.blog-image {
  width: 100%;
}
.blog-div {
  display: flex;
  justify-content: space-around;
}
.left-arrow {
  width: 10%;
  display: flex;
  justify-content: center;
  padding: 50px;
  height: 350px;
}
.right-arrow {
  width: 10%;
  display: flex;
  justify-content: center;
  padding: 50px;
  height: 350px;
}

.section-six {
  width: 100%;
  height: 450px;
  background: linear-gradient(180deg, #eaf0ff 0%, #f6f9ff 100%);
}
.testimonials {
  display: flex;
  width: 80%;
  margin: auto;
  box-sizing: border-box;
  padding-top: 4rem;
}
.left-div1 {
  width: 50%;
  margin: auto;
  padding: 2rem;
}
.right-div1 {
  width: 50%;
  margin: auto;
  box-sizing: border-box;
}
.qoute-div {
  height: 140px;
  width: 65%;
  background: #ffffff;
  border: 1px solid #d8e3fe;
  box-shadow: 0px 5px 50px #f3f5fa;
  padding: 2rem;
  margin: auto;
  display: flex;
  justify-content: center;
  margin-top: 3rem;
}
.left-div1 h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
}
.lefty {
  width: 70%;
  margin: auto;
}
.left-div1 h3 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 45px;
  color: #3d4f9f;
}
.left-div1 p {
  font-family: Open Sans;
  font-style: normal;
  font-weight: 600;
  font-size: 12px;
  line-height: 23px;
  letter-spacing: 0.03em;
  color: #a4abc8;
}
.qoute-div p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.03em;
  color: #676f95;
}
.picture {
  position: relative;
  top: -100px;
  left: 240px;
}

.section-seven {
  width: 100%;
  height: 950px;
  background: #ffffff;
  display: flex;
  justify-content: center;
}
.section-seven-main {
  width: 55%;
  margin: auto;
}
.line {
  border: 1px solid #d8e3fe;
  margin: 20px;
}
.faq-drop-down {
  margin-left: 50px;
}
.section-seven-main h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
  text-align: center;
  padding: 10px;
}
.section-seven-main h3 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 30px;
  text-align: center;
  color: #3d4f9f;
  padding: 10px;
}
.section-seven-main p {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 19px;
  display: flex;
  align-items: center;
  letter-spacing: 0.03em;
  color: #8e96b7;
}
.section-seven-main img {
  padding: 10px;
}
.FAQ-btn {
  width: 195px;
  height: 43px;
  background: #e8ecf4;
  border-radius: 2px;
  margin: 20px;
}
.section-eight {
  width: 100%;
  height: 447px;
  background: linear-gradient(229.32deg, #6888ff 12.77%, #5e80ff 73.11%);
}
.blue-cloud {
  width: 100%;
  display: flex;
  margin: auto;
}
.blue-cloud h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #ffffff;
  text-align: center;
  padding: 10px;
}
.blue-cloud h2 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 300;
  font-size: 48px;
  line-height: 60px;
  text-align: center;
  color: #ffffff;
  padding: 10px;
}
.blue-cloud p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 29px;
  text-align: center;
  letter-spacing: 0.03em;
  color: #ffffff;
}
.view-pricing-btn {
  width: 130px;
  height: 43px;
  background: #ffffff;
  box-shadow: 0px 5px 15px #6480e8;
  border-radius: 2px;
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #565f82;
  border: 0.5px solid #ffffff;
}
.docu-btn {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 13px;
  line-height: 16px;
  color: #c7d3ff;
  width: 155px;
  height: 43px;
  border: none;
  background: none;
  border: 0.2px solid #ffffff;
  border-radius: 2px;
}
.blue-cloud-text {
  width: 60%;
  margin: auto;
}
.blue-cloud2 {
  position: relative;
  right: 110px;
  margin-top: 10rem;
  width: 100%;
}
.blue-cloud-btn-div {
  display: flex;
  justify-content: center;
  padding: 10px;
}
.section-nine {
  width: 100%;
  height: 330px;
  background: #fcfdff;
  display: flex;
}
.section-nine-main {
  width: 60%;
  height: 200px;
  display: flex;
  margin: auto;
}
.left-div3 {
  width: 50%;
  padding: 50px;
}
.left-div3 h4 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 22px;
  color: #3d4f9f;
}
.left-div3 p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 27px;
  letter-spacing: 0.03em;
  color: #8d96bd;
}
.right-div3 {
  width: 50%;
  padding-top: 4rem;
}
.input-email {
  width: 50%;
  height: 59px;
  background: #efeff7;
  border-radius: 5px;
  padding: 10px;
  border: none;
}
.save-btn {
  width: 35%;
  height: 59px;
  background: #4d6ce1;
  box-shadow: 0px 5px 15px rgba(116, 104, 255, 0.2);
  border-radius: 5px;
  color: #ffffff;
  border: none;
}
</style>
