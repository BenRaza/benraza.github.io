<template>
  <div class = stars>
        <div class = twinkling></div>
  </div>
  <main>
    <div class="landing">
      <a href="#page2" class="portfolio"><h1>PORTFOLIO</h1></a>
      <h2 class = "name">Benjamin Razafimanantsoa</h2>
      <a href="#page2" class="anchor">
        <svg class="arrow" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
        </svg>
      </a>
    </div>
      <div class="page2" id="page2">
        <h2 class="who"> Who am I ? </h2>
        <div class="presentation">
          <h3> Hello there !</h3>
          <p>I hope you will enjoy your time spent on this website discovering all the projects I have done :)</p>
          <p>I'm a French student at the IMAC school (which stands for "Image, Multimedia, Audiovisual and Communication") and I'm currently involved in a student exchange programme in Canada.</p>
          <p>I do love discovering a lot of stuff, experimenting the unknown, and learning from people new ways of doing things and new ways of thinking.</p>
          <p>You will see here projects of all kinds, from motion design to 3D, a bit of video games and, as a bonus, some short films. Sometimes you will see some fusions of those kinds</p>
        </div>
        <a href="#contents" class="anchor2">
        <svg class="arrow" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
        </svg>
      </a>
    </div>
    <div class="contents" id="contents">
      <a href="#motion" class="contentWord">
        <h2> Motion Design</h2>
      </a>
      <a href="#3D" class="contentWord">
        <h2> 3D </h2>
      </a>
      <a href="#short" class="contentWord">
        <h2>Short Films</h2>
      </a>
    </div>
    <div class="part" id="motion">
      <h1 class="titlePart">Motion Design (After Effects)</h1>
      <div class="oneProject">
        <h2> Video Mapping in Chambon-sur-Voueize - France</h2>
        <div class="photos">
          <img :src="projects[12].url" class="photo">
          <img :src="projects[13].url" class="photo">
          <img :src="projects[14].url" class="photo">
        </div>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[15].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
          <p>for the full project click <a href="https://lesallumeursdereves.com/les-spectacles/creuse-confluence/">here</a></p>
      </div>
      <div class="oneProject">
        <h2> Video Mapping in Annemasse - France</h2>
        <div class="photos">
          <img :src="projects[8].url" class="photo">
          <img :src="projects[9].url" class="photo">
          <img :src="projects[10].url" class="photo">
        </div>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[11].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
          <p>for the full project click <a href="https://lesallumeursdereves.com/les-spectacles/annemasse-mairie/">here</a></p>
      </div>
      <div class="oneProject">
        <h2> "Purple Hat" video clip (only on After Effects)</h2>
        <div class="photos">
          <img :src="projects[0].url" class="photo">
          <img :src="projects[1].url" class="photo">
          <img :src="projects[2].url" class="photo">
        </div>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[3].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Parody project for the integration weekend of my university (cheap on purpose) </h2>
        <div class="photos">
          <img :src="projects[4].url" class="photo">
          <img :src="projects[5].url" class="photo">
          <img :src="projects[6].url" class="photo">
        </div>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[7].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Some random stuff I made with After Effects</h2>
        <div class="photos">
          <img :src="projects[16].url" class="photo">
          <img :src="projects[17].url" class="photo">
          <img :src="projects[18].url" class="photo">
        </div>
        <div class="photos">
          <img :src="projects[19].url" class="photo">
          <img :src="projects[20].url" class="photo">
          <img :src="projects[21].url" class="photo">
        </div>
      </div>
    </div>
    <div class="part" id="3D">
      <h1 class="titlePart"> 3D : Animation, Modelling, Composition and lighting</h1>
      <div class="oneProject">
        <h2> Knight Animation Motion Capture (Unreal Engine)</h2>
        <div class="photos">
          <img :src="projects[22].url" class="photo">
          <img :src="projects[23].url" class="photo">
          <img :src="projects[24].url" class="photo">
        </div>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[25].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Bat Animation (3DSmax - Arnold) </h2>
        <div class="photos">
          <img :src="projects[26].url" class="photo">
          <img :src="projects[27].url" class="photo">
          <img :src="projects[28].url" class="photo">
        </div>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[29].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Ekko animation (Maya)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[30].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Micro-environment : Modelling Xerneas and Regice (3DSmax - Arnold) </h2>
        <div class="photos">
          <img :src="projects[31].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Street composition and lightning (3DSmax - Arnold) </h2>
        <div class="photos">
          <img :src="projects[32].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Lab composition and lightning (Maya - Unreal Engine) </h2>
        <div class="photos">
          <img :src="projects[33].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Creation of a fan in Pop Art style (3DSmax - Blender)</h2>
        <div class="photos">
          <img :src="projects[34].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Modelling of a simple house (3DSmax - Arnold)</h2>
        <div class="photos">
          <img :src="projects[35].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Modelling and animation (Blender - Cycles)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[36].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> SawMill Killers (Unreal Engine)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[41].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Immersive room (Unity) - Project in production</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[39].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
    </div>
    <div class="part" id="short">
      <h1 class="titlePart"> Short films </h1>
      <div class="oneProject">
        <h2> SuperVision </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[37].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Suis-moi </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[38].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Tu te fais des films </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[40].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
    </div>
    <div class="presentation">
          <h3> Oh, you've made it this far!</h3>
          <p>I hope you've enjoyed the little trip I've organised for you.</p>
          <p>Thank you for your time.</p>
          <p>Kisses :*</p>
        </div>
  </main>

</template>

<script>

export default {
  data() {
    return {
      projects: [
        { type: 'image', url: '/images/imagePurple1.png', title:'PurpleImage1'},
        { type: 'image', url: '/images/imagePurple2.png', title:'PurpleImage2'},
        { type: 'image', url: '/images/imagePurple3.png', title:'PurpleImage3'},
        { type: 'youtube', url: '1pqh85qjtHQ', title: 'PurpleHat'},
        { type: 'image', url: '/images/pokemon1.png', title:'Pokemon1'},
        { type: 'image', url: '/images/pokemon2.png', title:'Pokemon2'},
        { type: 'image', url: '/images/pokemon3.png', title:'Pokemon3'},
        { type: 'youtube', url: 'qarZGteDU_U', title: 'Pokemon'},
        { type: 'image', url: '/images/Annemasse1.png', title:'Annemasse1'},
        { type: 'image', url: '/images/Annemasse2.png', title:'Annemasse2'},
        { type: 'image', url: '/images/Annemasse3.png', title:'Annemasse3'},
        { type: 'youtube', url: 'lNpP05euPMs', title: 'Annemasse'},
        { type: 'image', url: '/images/Chambon1.png', title:'Chambon1'},
        { type: 'image', url: '/images/Chambon2.png', title:'Chambon2'},
        { type: 'image', url: '/images/Chambon3.png', title:'Chambon3'},
        { type: 'youtube', url: 'NfBUk3RDKKY', title: 'Chambon'},
        { type: 'image', url: '/images/Course.gif', title: 'Course'},
        { type: 'image', url: '/images/nullos.gif', title: 'BoucheB'},
        { type: 'image', url: '/images/title_1.gif', title: 'Title'},
        { type: 'image', url: '/images/green_eye.gif', title: 'Green'},
        { type: 'image', url: '/images/ekko.gif', title: 'Ekko'},
        { type: 'image', url: '/images/white_eyes_1.gif', title: 'White'},
        { type: 'image', url: '/images/chato1.png', title: 'chato1'},
        { type: 'image', url: '/images/chato2.png', title: 'chato2'},
        { type: 'image', url: '/images/chato3.png', title: 'chato3'},
        { type: 'youtube', url: '7N5CIs5bvyk', title: "chato"},
        { type: 'image', url: '/images/chauve1.png', title: 'chauve1'},
        { type: 'image', url: '/images/chauve2.png', title: 'chauve2'},
        { type: 'image', url: '/images/chauve3.png', title: 'chauve3'},
        { type: 'youtube', url: 'nQPEu6F9Ogs', title: "chauve"},
        { type: 'youtube', url: 'rzwgPHCdb10', title: "ekko"},
        { type: 'image', url: '/images/render_v2.jpg', title: 'Xerneas'},
        { type: 'image', url: '/images/rue.jpg', title: 'Street'},
        { type: 'image', url: '/images/labo.jpg', title: 'Lab'},
        { type: 'image', url: '/images/EXPORTED_TIM.jpg', title: 'Tim_Hortons'},
        { type: 'image', url: '/images/maison.jpg', title: 'Maison'},
        { type: 'youtube', url: 'Fr8sFDADLhc', title: "blender"},
        { type: 'youtube', url: '7rOS_-JRPR0', title: "SuperVision"},
        { type: 'youtube', url: '_0ECGu1mgd4', title: "Suis-moi"},
        { type: 'youtube', url: 'EXLm_GHmlRI', title: "Immersive"},
        { type: 'youtube', url: 'EkPQN0nGZ7M', title: "ttfdf"},
        { type: 'youtube', url: 'Hb6OUEwCYPc', title: "sawmill"},
      ]
    }
  }
}

</script>


<style scoped>
main {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  margin-bottom: 100px;
  font-family: 'Salsa', cursive;
}

h1 {
  color: white;
  font-size: 50px;
}

h2 {
  color: white;
  font-size: 40px;
  letter-spacing: 2px;
  text-align: center;
}

.who{
  animation: 4s ease-in-out who infinite alternate;
}

@keyframes who{
  0% {
    transform: translate(0, 0) rotate(-3deg);
  }
  50% {
    transform: translate(0, 15px) rotate(0deg);
  }
  100%{
    transform: translate(0, 0) rotate(3deg);
  }
}

h3 {
  color: white;
  font-size: 30px;
  letter-spacing: 2px;
  margin-bottom: 40px;
  text-align: center;
}

p {
  color: white;
  font-size: 20px;
  letter-spacing: 1px;
  text-align: center;
  margin-bottom: 10px;
}

img {
  border-radius: 7px;
  width: 100%;
}

.landing {
  height: 100vh;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  position: relative;
}

.anchor{
  outline: none;
  border: 2px solid #e9fab2;
  border-radius: 50%;
  position: absolute;
  left: 50%;
  bottom: 75px;
  width: 50px;
  height: 50px;
  color: #e9fab2;
  cursor: pointer;
  animation: 0.5s ease-in-out anchor infinite alternate;
  display: flex;
  justify-content: center;
  align-items: center;
}

.anchor svg {
  width: 60%;
}

@keyframes anchor{
  from {
    transform: translate(-50%, 0);
  }
  to {
    transform: translate(-50%, 10px);
  }
}

.portfolio {
  outline: none;
  border: none;
}

.anchor2{
  outline: none;
  border: 2px solid #e9fab2;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  color: #e9fab2;
  cursor: pointer;
  animation: 0.5s ease-in-out anchor2 infinite alternate;
  display: flex;
  justify-content: center;
}
.anchor2 svg {
  width: 60%;
}

@keyframes anchor2{
  from {
    transform: translate(0, 0);
  }
  to {
    transform: translate(0, 10px);
  }
}

.portfolio h1 {
  text-align: center;
  font-size: 10vw;
  color: #e9fab2;
  cursor: pointer;
  transition: 0.3s ease-in-out;
  text-shadow: #0000 1px 1px 0px;
  user-select: none;
  font-family: 'Rubik Doodle Shadow', system-ui;
  letter-spacing: 5px;
}

.portfolio h1:hover{
  transition: 0.3s ease-in-out;
  text-shadow: #FC0 1px 1px 30px;
  color: #E7F96C;
  letter-spacing: 8px;
  transform: scale(101%);
}

.name:hover{
  transition: 0.2s ease-in-out;
  text-shadow: #FC0 1px 1px 15px;
  letter-spacing: 3px;
}

.name {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  font-size: 4vw;
  margin-top: 2vh;
  color: #e9fab2;
  transition: 0.3s ease-in-out;
  text-shadow: #0000 1px 1px 0px;
  user-select: none;
  text-align: center;
  margin-bottom: 6vh;
  letter-spacing: 2px;
}

.page2 {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: space-around;
  margin-left: 20px;
  margin-right: 20px;
  height: 100vh;
}
.presentation {
  display: flex;
  flex-flow: column;
  margin-left: 7vw;
  margin-right: 7vw;
  padding: 20px;
  border: 2px solid #e9fab2;
  border: 50%;
  padding-top: 50px;
  padding-bottom: 50px;
  border-style: groove;
}

.contents {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-evenly;
  align-items: center;
  width: 80%;
  height: 100vh;
}

.contentWord {
  display: flex;
  justify-content: center;
  align-items: center;
  width : 200px;
  height: 200px;
  border: 2px solid #e9fab2;
  border: 50%;
  border-style: outset;
  transition: 0.3s ease-in-out;
}

.contentWord:hover{
  transition: 0.3s ease-in-out;
  text-shadow: #FC0 1px 1px 30px;
  color: #E7F96C;
  letter-spacing: 8px;
  transform: scale(101%);
}

.part{
  display: flex;
  flex-flow: column;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  width: 80%;
}

.titlePart{
  margin: 50px;
  margin-bottom: 200px;
  font-family: 'Rubik Doodle Shadow', system-ui;
  color: #e9fab2;
  text-shadow: #FC0 1px 1px 2px;
  letter-spacing: 3px;
  text-align: center;
}

.oneProject{
  display: flex;
  flex-flow: column;
  justify-content: center;
  max-width: 1200px;
  width: 100%;
  margin-bottom: 30vh;
}

.photos{
  display: flex;
  flex-flow: row;
  justify-content: space-between;
  margin-bottom: 15px;
  padding-top: 50px;
}

.photo{
  width: 30%;
}

.video{
  width: 100%;
  margin-top: 15px;
  padding-bottom: 56.25%;
  position: relative;
}
.video > * {
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0px;
  top: 0px;
  border: none;
}

.projects {
  max-width: 1200px;
  width: 80%;
}

.project {
  margin: 50px 0;
}


</style>

