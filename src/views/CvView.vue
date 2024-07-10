<template>
  <section class="about">
    <!-- 0 header -->
    <header class="top" style="background-color: black">
      <div class="container" id="home">
        <nav class="navbar">
          <div class="icon2sy">
            <a href class="brand-link">
              <span class="char" style="background-color:red;">B</span>Blinder
              <span class="sec-name">Front</span>
            </a>
          </div>
          <ul class="nav-list" id="navi-list">
            <li class="list-item">
              <a href="#home" class="ref">Home</a>
            </li>
            <li class="list-item">
              <a href="#Services" class="ref">Services</a>
            </li>
            <li class="list-item">
              <a href="#About" class="ref">About me</a>
            </li>
            <li class="list-item">
              <a href="#Projects" class="ref">Projects</a>
            </li>
          </ul>
          <div class="menu" id="toggle-button" @click="toggleMenu">
            <div class="menu-line"></div>
            <div class="menu-line"></div>
            <div class="menu-line"></div>
          </div>
        </nav>
      </div>
    </header>
    <!-- 1 header -->
    <!-- 0 top2-->
    <section class="land-top" id="home">
      <div
        class="container"
        style="display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;"
      >
        <h1 class="top-head" style="margin-top: 80px;">Web & Front-end Designer</h1>
        <p class="bio">
          Hardworking professional skilled in Vue.js. Passionate about secure,
          optimized code. Eager to tackle new challenges and leverage cutting-edge technologies for impactful projects.
        </p>
        <div class="min-projects">
          <div class="projects-title">
            <h2>top of The Last Projects</h2>
            <p>the most desired Projects</p>
          </div>
          <!-- #1st -->
          <a href="/fash/index.html" class="project" target="_blank">
            <img src="../assets/img/imgs/gallery-01.png" alt="none" class="p-cover" />
            <div class="info">
              <h2 class="p-title">Fashoin</h2>
            </div>
            <p>good design for fashoin ideas</p>
          </a>
          <!-- #2sd -->
          <a href="aqart/index.html" class="project" target="_blank">
            <img src="../assets/img/imgs/gallery-02.png" alt="none" class="p-cover" />
            <div class="info">
              <h2 class="p-title">Aqar Bot</h2>
            </div>
            <p>Landing page describe Bot</p>
          </a>
          <!-- #3rd -->
          <a href="/Scale/asset.html" class="project" target="_blank">
            <img src="../assets/img/pro1.png" alt="none" class="p-cover" />
            <div class="info">
              <h2 class="p-title">Scal</h2>
            </div>
            <p>Exam for students</p>
          </a>
          <!-- #4th -->
          <a href="#Projects" class="more">
            <div class="sub-more">
              <p class="p-link">More Projects</p>
            </div>
            <img src="../assets/img/arrow-left.png" class="icon2 arrow" />
          </a>
        </div>
      </div>
    </section>
    <!-- 1 top2 -->
    <!--  <div class=""></div> -->
    <!-- 1 jops  -->
    <section class="jops" id="Services">
      <div class="container">
        <div class="services-tilte">
          <span>what I can do</span>
          <h2>
            I work
            <br />Performed For
            <br />Client happy
          </h2>
          <button>View All services</button>
        </div>

        <div class="services">
          <div class="service">
            <img src="../assets/img/blog.png" class="icon2" />
            <div class="serv-info">
              <h3>Web design</h3>
              <p>I can Design UI for system Reaquiment</p>
              <a href>Read more</a>
            </div>
          </div>

          <div class="service">
            <img src="../assets/img/cloud-computing.png" class="icon2" />
            <div class="serv-info">
              <h3>Developing</h3>
              <p>I can Modfy your current project</p>
              <a href>Read more</a>
            </div>
          </div>

          <div class="service">
            <img src="../assets/img/code.png" class="icon2" />
            <div class="serv-info">
              <h3>Ui Coding</h3>
              <p>If you have PSD file or any ui a can code it</p>
              <a href>Read more</a>
            </div>
          </div>

          <div class="service">
            <img src="../assets/img/multi-channel.png" class="icon2" />
            <div class="serv-info">
              <h3>Api Connects</h3>
              <p>have problem with connect front & Back ?</p>
              <a href>Read more</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- 1 jops  -->
    <!-- 1 about me  -->
    <section class="about-me" id="About">
      <div class="container">
        <div class="about-me-info">
          <div class="services-tilte">
            <span>About me</span>
            <h2>Direction With Me.</h2>
            <p>
              Since 2020 I have served as a Front-end Developer,
              <br />where I have Develop
              many Systems ..
              <br />I also provide high-quality designs at the lowest possible cost ..
              <br />Which
              gives me a high chance for Make your website ..
            </p>
            <div class="meddile-about">
              <img src="../assets/img/trophy.png" class="icon2-L icon2-left" />
              <div>
                <h3 class="mession-h">My Mession</h3>
                <p>
                  I want to be best front-end in egypt and The Arab world
                  <br />make full websites make eyes happy
                </p>
              </div>
              <img src="../assets/img/eagle.png" class="icon2-L icon2-right" />
            </div>
            <button class="about-btn">About more</button>
          </div>
        </div>
        <div class="photo-box">
          <div class="photoo">
            <img src="../assets/img/3.jpg" />
          </div>
        </div>
      </div>
    </section>
    <!-- 1  about me  -->
    <!--  -->
    <section class="facts">
      <div class="container">
        <div class="fact">
          <img src="../assets/img/list.png" class="icon2-m" />
          <h2 class="number">27</h2>
          <h3>Projects completed</h3>
        </div>
        <div class="fact">
          <img src="../assets/img/reputation.png" class="icon2-m" />
          <h2 class="number">10</h2>
          <h3>satisfied clients</h3>
        </div>
        <div class="fact">
          <img src="../assets/img/responsive.png" class="icon2-m" />
          <h2 class="number">3</h2>
          <h3>Years experience</h3>
        </div>
        <div class="fact">
          <img src="../assets/img/trustworthiness.png" class="icon2-m" />
          <h2 class="number">11</h2>
          <h3>Certificates</h3>
        </div>
      </div>
    </section>
    <!--  -->
    <!-- Start Gallery -->
    <div class="black" id="Projects">
      <div class="container">
        <div class="head-projects">
          <h2 class="main-title">Projects</h2>
          <button  @click="showo">View All</button>
        </div>
      </div>
    </div>
    <div class="gallery" id="gallery">
      <div class="container">
        <a href="/fash/index.html" class="box" target="_blank">
          <div class="infoo">
            <h2>Fashoin</h2>
            <h2>
              8
              <img src="../assets/img/star.png" class="icon2" />
            </h2>
          </div>
          <div class="image">
            <img src="../assets/img/imgs/gallery-01.png" alt />
          </div>
        </a>
        <a href="aqart/index.html" class="box" target="_blank">
          <div class="infoo">
            <h2>Aqar Bot</h2>
            <h2>
              7
              <img src="../assets/img/star.png" class="icon2" />
            </h2>
          </div>
          <div class="image">
            <img src="../assets/img/imgs/gallery-02.png" alt />
          </div>
        </a>
        <a href="/Scale/asset.html" class="box" target="_blank">
          <div class="infoo">
            <h2>Scale</h2>
            <h2>
              6
              <img src="../assets/img/star.png" class="icon2" />
            </h2>
          </div>
          <div class="image">
            <img src="../assets/img/imgs/gallery-03.png" alt />
          </div>
        </a>
        <a href="furniture/index.html" class="box" target="_blank">
          <div class="infoo">
            <h2>Tumpas</h2>
            <h2>
              8
              <img src="../assets/img/star.png" class="icon2" />
            </h2>
          </div>
          <div class="image">
            <img src="../assets/img/imgs/gallery-04.png" alt />
          </div>
        </a>
        <a href="Corpo-link/index.html" class="box" target="_blank">
          <div class="infoo">
            <h2>Corpo Link</h2>
            <h2>
              8
              <img src="../assets/img/star.png" class="icon2" />
            </h2>
          </div>
          <div class="image">
            <img src="../assets/img/imgs/gallery-05.png" alt />
          </div>
        </a>
        <span class="box curser" @click="showo">
          <div class="infoo">
            <h2></h2>
            <h2></h2>
          </div>
          <div class="image flexe">
            <h1> +22 More</h1>
            <button>View</button>
          </div>
        </span>
      </div>
    </div>
    <div class="gallery" v-if="shows === '1'">
      <div class="container">
        <a href="/fash/index.html" class="box" target="_blank">
          <div class="infoo">
            <h2>Mallory</h2>
            <h2>
              8
              <img src="../assets/img/star.png" class="icon2" />
            </h2>
          </div>
          <div class="image">
            <img src="../assets/img/imgs/gallery-06.png" alt />
          </div>
        </a>
        
      </div>
    </div>
    <!-- End Gallery -->
  </section>
</template>

<script>
export default {
  data() {
    return {
      shows: "0"
    };
  },
  methods: {
    toggleMenu() {
      const naviList = document.getElementById("navi-list");
      naviList.classList.toggle("active");
    },
    showo() {
      this.shows = this.shows === "0" ? "1" : "0";
    }
  }
};
</script>

<style scoped>
@import "@/assets/style.css";
@import "@/assets/normalize.css";
</style>
