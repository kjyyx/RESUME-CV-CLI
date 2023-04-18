<template>
  <section class="main-section">
    <div class="left-part">
      <div class="photo-container">
        <img src="images/kpj.png" />
      </div>
      <div class="contact-container">
        <h2 class="title">Contact Me</h2>
        <div class="contact-list">
          <div class="icon-container">
            <i class="bi bi-geo-alt-fill"></i>
          </div>
          <div class="contact-text">
            <p>Rosana St. Balibago, Angeles City 2009</p>
          </div>
        </div>
        <div class="contact-list">
          <div class="icon-container">
            <i class="bi bi-envelope-fill"></i>
          </div>
          <div class="contact-text">
            <p>kpjaculbia@student.hau.edu.ph</p>
          </div>
        </div>
        <div class="contact-list">
          <div class="icon-container">
            <i class="bi bi-laptop"></i>
          </div>
          <div class="contact-text">
            <p>091901234567</p>
          </div>
        </div>
      </div>

      <div class="education-container">
        <h2 class="title">Education</h2>
        <div class="course">
          <h5 class="college-name">
            Rafael L. Lazatin Memorial HighSchool (R.L.L.M.H.S.)
          </h5>
          <p class="education-details">
            P.M. Pabalan St., Don PepeSubdivision Balibago, Angeles City Junior
            High School | With Honors
          </p>
          <p class="education-date">2015-2019</p>
        </div>
        <div class="course">
          <h2 class="education-title">
            Mobile Application and Web Development
          </h2>
          <h5 class="college-name">STI College Angeles</h5>
          <p class="education-details">
            Agson Bldg. Mc Arthur HighwayBalibago, Angeles City Senior High
            School | With Honors
          </p>
          <p class="education-date">2019-2021</p>
        </div>
      </div>

      <div class="skills-container">
        <h2 class="title">Skills</h2>
        <div class="skill">
          <div class="left-skill">
            <p>SQL</p>
          </div>
          <div class="right-skill">
            <div class="outer-layer">
              <div class="inner-layer" style="width: 60%"></div>
            </div>
          </div>
        </div>
        <div class="skill">
          <div class="left-skill">
            <p>Python</p>
          </div>
          <div class="right-skill">
            <div class="outer-layer">
              <div class="inner-layer" style="width: 90%"></div>
            </div>
          </div>
        </div>
        <div class="skill">
          <div class="left-skill">
            <p>C and C++</p>
          </div>
          <div class="right-skill">
            <div class="outer-layer">
              <div class="inner-layer" style="width: 40%"></div>
            </div>
          </div>
        </div>
        <div class="skill">
          <div class="left-skill">
            <p>JavaScript</p>
          </div>
          <div class="right-skill">
            <div class="outer-layer">
              <div class="inner-layer" style="width: 60%"></div>
            </div>
          </div>
        </div>
        <div class="skill">
          <div class="left-skill">
            <p>Java</p>
          </div>
          <div class="right-skill">
            <div class="outer-layer">
              <div class="inner-layer" style="width: 70%"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="right-part">
      <div class="banner">
        <h1 class="firstname">Kenji Palawan</h1>
        <h1 class="lastname">Jaculbia</h1>
        <p class="position">STUDENT | Website Developer</p>
      </div>

      <div class="school-container">
        <h2 class="title text-left">School Experience</h2>
        <div class="school">
          <h2 class="company-name">Objective</h2>
          <p class="school-text">
            To obtain a challenging positionthat will further enhance
            myinnovativeness and to contributefor a growth-oriented
            positionwhere ability, knowledge andeducation can be utilized
            towardsthe advancement or thedevelopment of the company andpersonal
            goals.
          </p>
        </div>

        <div class="school">
          <h2 class="company-name">Expertise</h2>
          <p class="school-text">
            I am a hardschooling, quick learner who is knowledgeable in
            Microsoft Office365 and its structure. I am able to school both
            individually and in a team, and I have some experience in
            programming languages such as Java and Python. Additionally, I have
            good communication skills.
          </p>
        </div>
        <div class="school">
          <h2 class="company-name">Certifications and Affiliations</h2>
          <p class="school-text">
            Director's Cut (Video making) <br />
            2nd Runner Up | 02/06/2020 <br />
            Quiz Bee Competition <br />
            2nd place | 07/31/19
          </p>
          <p class="school-text">
            <br />Logic Breaker Club | 2020-2021 <br />
            Science Club | 2015-2019
          </p>
        </div>
      </div>

      <div class="references-container">
        <h2 class="title text-left">References</h2>
        <div class="references">
          <div class="left-references">
            <h4 class="name">Ms. Pinky Mae Gueco, LPT</h4>
            <p class="company-name">Instructor | STI College Angeles</p>
            <div class="phone">
              <div class="phone-text">
                <p>Phone:</p>
                <p>Email:</p>
              </div>
              <div class="phone-number">
                <p>+63 975 7229 931</p>
                <p>guecopinky07@gmail.com</p>
              </div>
            </div>
          </div>
          <div class="right-references">
            <h4 class="name">Ms. Odessa Rosario, LPT</h4>
            <p class="company-name">
              General Education Teacher | STI College Angeles
            </p>
            <div class="phone">
              <div class="phone-text">
                <p>Phone:</p>
                <p>Email:</p>
              </div>
              <div class="phone-number">
                <p>+63 935 0959 425</p>
                <p>odessacrosario@gmail.com</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Public+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body {
  background-color: #ebecf0;
  padding: 100px;
  margin: 10px;
}

.main-section {
  width: 210mm;
  height: 297mm;
  background-color: white;
  margin: 0 auto;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  display: flex;
}

.main-section .left-part {
  width: 40%;
  height: 100%;
  background-color: #444444;
  padding: 2.8rem;
}

.left-part .photo-container {
  margin-bottom: 2.2rem;
}

.left-part .photo-container img {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  border: 1rem solid white;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
}

.title {
  font-family: 'Public Sans', sans-serif;
  font-size: 1.4rem;
  text-transform: uppercase;
  padding: 0.6rem;
  background-color: #00a138;
  color: white;
  text-align: center;
  margin: 1.4rem 0;
}

.contact-container {
  margin-bottom: 2.2rem;
}

.contact-container .contact-list {
  display: flex;
  gap: 1rem;
  margin-bottom: 1rem;
  font-family: 'Lato', sans-serif;
  color: #ffffff;
  font-size: 1rem;
}

.education-container {
  margin-bottom: 2.2rem;
  font-family: 'Lato', sans-serif;
}

.education-container .course {
  margin-bottom: 1rem;
  color: #ffffff;
}

.education-container .education-title {
  font-size: 1rem;
  font-weight: 800;
  margin-bottom: 0.3rem;
}

.education-container .college-name {
  margin-bottom: 0.3rem;
  font-weight: 600;
}

.education-container .education-date {
  font-size: 0.9rem;
}

.education-container .education-details {
  font-size: 0.9rem;
}

.skills-container .skill {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.6rem;
  font-family: 'Lato', sans-serif;
  color: #ffffff;
}

.skills-container .skill .right-skill .outer-layer {
  background-color: #bbbbbb;
  height: 0.4rem;
  width: 5rem;
  border-radius: 0.4rem;
}

.skills-container .skill .right-skill .inner-layer {
  background-color: #00a138;
  height: 100%;
  border-radius: inherit;
}

.right-part {
  padding: 2.8rem;
}

.right-part .banner {
  font-family: 'Open Sans', sans-serif;
  color: #4d4d4f;
  margin-bottom: 2.2rem;
}

.right-part .banner .firstname {
  font-size: 3rem;
}

.right-part .banner .lastname {
  font-size: 3rem;
  font-weight: 400;
  letter-spacing: 0.5rem;
  margin-top: -1rem;
}

.right-part .banner .position {
  letter-spacing: 0.3rem;
  margin-top: -0.5rem;
  font-size: 1.1rem;
  padding: 10px 0;
}

.school-container {
  margin-top: 5rem;
  font-family: 'Lato', sans-serif;
}

.school-container .school:not(:last-child) {
  margin-bottom: 1.8rem;
}

.school-container .school .job-date {
  display: flex;
  justify-content: space-between;
  color: #4d4d4f;
  margin-bottom: 0.5rem;
  font-size: 0.7rem;
  font-weight: 500;
}

.school-container .school .company-name {
  font-size: 0.9rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  color: #4d4d4f;
}

.school-container .school .school-text {
  color: #737373;
  font-size: 0.8rem;
  text-align: justify;
  line-height: 1rem;
}

.references-container .references {
  display: flex;
  justify-content: space-between;
  margin-top: 1rem;
  font-family: 'Lato', sans-serif;
  color: #00a138;
  padding: 10px;
}

.references-container .references .name {
  font-weight: 800;
  font-size: 1.1rem;
}

.references-container .references .company-name {
  margin: 0.5rem 0;
  font-size: 0.9rem;
}

.references-container .references .phone {
  display: flex;
  justify-content: space-between;
  font-size: 0.7rem;
  color: #414042;
}
.references-container .references .phone p {
  margin: 0.4rem 0;
}

.references-container .references .phone .phone-text {
  font-weight: 600;
}

.text-left {
  text-align: left;
}
</style>
