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
          <p>You will see here projects of all kinds, from motion design to 3D, a bit of video games and, as a bonus, some short films.</p>
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
      <h1 class="titlePart">Motion Design</h1>
      <div class="oneProject">
        <h2> "Purple Hat" video clip</h2>
        <div class="photos">
          <img :src="projects[0].url" class="photo">
          <img :src="projects[1].url" class="photo">
          <img :src="projects[2].url" class="photo">
        </div>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[3].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>

    </div>
    <!-- <div class="projects" id="projects">
      <div class="project" v-for="(project, index) in projects" :key="index">
        <template v-if="project.type === 'image'">
          <img :src="project.url">
          <p>{{ project.title }}</p>
        </template>
        <template v-if="project.type === 'youtube'">
          <iframe width="560" height="315" :src="`https://www.youtube.com/embed/${project.url}`" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </template>
      </div>
    </div> -->
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
        { type: 'youtube', url: 'LFr2LjZrts4', title: 'Test3'},
        { type: 'image', url: '/images/Cours_Recre1.jpg', title: 'Cours1'},
        { type: 'image', url: '/images/Cours_Recre2.jpg', title: 'Cours2'},
        { type: 'image', url: '/images/Course.gif', title: 'Course'},
        { type: 'image', url: '/images/EXPORTED_TIM.jpg', title: 'Tim_Hortons'},
        { type: 'image', url: '/images/labo.jpg', title: 'Lab'},
        { type: 'image', url: '/images/maison.jpg', title: 'Maison'},
        { type: 'image', url: '/images/modelisation1.jpg', title: 'Screen_Blender'},
        { type: 'image', url: '/images/nullos.gif', title: 'BoucheB'},
        { type: 'image', url: '/images/render_v2.jpg', title: 'Xerneas'},
        { type: 'image', url: '/images/rue.jpg', title: 'Street'},


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
  justify-content: center;
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

