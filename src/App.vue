<template>
  <div class = stars>
        <div class = twinkling></div>
  </div>
  <main>
    <div class="landing">
      <a href="#page2" class="portfolio"><h1>PORTFOLIO</h1></a>
      <a href="#page2"><h2 class = "name">Benjamin Razafimanantsoa</h2></a>
      <a href="#page2" class="anchor">
        <svg class="arrow" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
        </svg>
      </a>
    </div>
      <div class="page2" id="page2">
        <h2 class="who"> Qui suis-je ? </h2>
        <div class="presentation">
          <h3> Salutations !</h3>
          <p>J'espère que vous passerez un bon moment sur ce site en découvrant tous les projets que j'ai réalisés :)</p>
          <p>J'ai terminé mon cursus à l'école d'ingénieur IMAC (« Image, Multimédia, Audiovisuel et Communication ») et j'ai effectué un échange universitaire au Québec à l'UQAT en création numérique.</p>
          <p>J'aime découvrir beaucoup de choses, expérimenter l'inconnu et apprendre des gens de nouvelles façons de faire et de penser.</p>
          <p>Vous verrez ici des projets de toutes sortes, des jeux vidéo, des créations en 3D, du motion design et, en prime, quelques courts métrages. Parfois, vous verrez des fusions de tout cela.</p>
        </div>
        <a href="#reel" class="anchor2">
          <svg class="arrow" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
          </svg>
        </a>
      </div>
      <div class="reel" id="reel">
      <h2> ShowReel </h2>
      <div class="video">
        <iframe :src="`https://www.youtube.com/embed/${projects[42].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      </div>
      <a href="#contents" class="anchor2">
        <svg class="arrow" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
        </svg>
      </a>
    </div>
    <div class="contents" id="contents">
      <a href="#VG" class="contentWord">
        <h2> Jeu Video</h2>
      </a>
      <a href="#3D" class="contentWord">
        <h2> 3D </h2>
      </a>
      <a href="#motion" class="contentWord">
        <h2> Motion Design</h2>
      </a>
      <a href="#short" class="contentWord">
        <h2>Film</h2>
      </a>
    </div>
    <div class="part" id="VG">
      <h1 class="titlePart"> Jeux Vidéos et Expériences Immersives</h1>
      <div class="oneProject">
        <h2> Stage : SIMAPTIC </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[48].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Experience Immersive : StoryTail </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[47].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Bring me red (Unreal Engine) </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[43].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
        <h3></h3>
      </div>
      <div class="oneProject">
        <h2> Trapped (Unreal Engine) </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[44].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
        <h3></h3>
      </div>
      <div class="oneProject">
        <a href="https://thepaqui.itch.io/gcc0-let-it-burn" target="_blank"><h2> Let it Burn (Unity) </h2></a>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[45].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
        <h3></h3>
      </div>
      <div class="oneProject">
        <h2> La Volonté de Fer (Unity) </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[46].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
        <h3></h3>
      </div>
      <div class="oneProject">
        <h2> Speedy Delivery (Unity) </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[49].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
        <h3></h3>
      </div>
    </div>
    <div class="part" id="3D">
      <h1 class="titlePart"> 3D : Animation, Modelisation, Composition and Eclairage</h1>
      <div class="oneProject">
        <h2> Animation Cinematique et Motion Capture (Unreal Engine)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[25].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Machinima GTA V</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[51].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> SawMill Killers (Unreal Engine)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[41].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      
      <div class="oneProject">
        <h2> Réveil aux aurores (3DSmax - Arnold) </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[29].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Animation d'Ekko (Maya)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[30].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Micro-environment : Modélisation de Xerneas et Regice (3DSmax - Arnold) </h2>
        <div class="photos">
          <img :src="projects[31].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Composition et éclairage (3DSmax - Arnold) </h2>
        <div class="photos">
          <img :src="projects[32].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Composition et éclairage (Maya - Unreal Engine) </h2>
        <div class="photos">
          <img :src="projects[33].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Modelisation d'un faux ventilateur style Pop Art (3DSmax - Blender)</h2>
        <div class="photos">
          <img :src="projects[34].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Modelisation d'une maison simpliste (3DSmax - Arnold)</h2>
        <div class="photos">
          <img :src="projects[35].url">
        </div>
      </div>
      <div class="oneProject">
        <h2> Modelisation et Animation (Blender - Cycles)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[36].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
    </div>
    <div class="part" id="motion">
      <h1 class="titlePart">Motion Design (After Effects)</h1>
      <div class="oneProject">
        <h2> Doga </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[50].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Video Mapping à Chambon-sur-Voueize - France</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[15].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
          <p> projet entier ici <a href="https://lesallumeursdereves.com/les-spectacles/creuse-confluence/">here</a></p>
      </div>
      <div class="oneProject">
        <h2> Video Mapping à Annemasse - France</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[11].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
          <p> projet entier ici <a href="https://lesallumeursdereves.com/les-spectacles/annemasse-mairie/">here</a></p>
      </div>
      <div class="oneProject">
        <h2> "Purple Hat" clip video (After Effects)</h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[3].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
      <div class="oneProject">
        <h2> Projet parodique Pokemon pour le week-end d'intégration de mon université </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[7].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
    </div>
    <div class="part" id="short">
      <h1 class="titlePart"> Short films </h1>
      <div class="oneProject">
        <h2> Tu te fais des films </h2>
        <div class="video">
          <iframe :src="`https://www.youtube.com/embed/${projects[40].url}?rel=0`" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
      </div>
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
    </div>
    <div>
          <h3> FIN </h3>
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
        { type: 'youtube', url: 'i-bn4UjC4d0', title: "chato"},
        { type: 'image', url: '/images/chauve1.png', title: 'chauve1'},
        { type: 'image', url: '/images/chauve2.png', title: 'chauve2'},
        { type: 'image', url: '/images/chauve3.png', title: 'chauve3'},
        { type: 'youtube', url: 'I3PMl1Za9YU', title: "chauve"},
        { type: 'youtube', url: 'rzwgPHCdb10', title: "ekko"},
        { type: 'image', url: '/images/render_v2.jpg', title: 'Xerneas'},
        { type: 'image', url: '/images/rue.jpg', title: 'Street'},
        { type: 'image', url: '/images/labo.jpg', title: 'Lab'},
        { type: 'image', url: '/images/EXPORTED_TIM.jpg', title: 'Tim_Hortons'},
        { type: 'image', url: '/images/maison.jpg', title: 'Maison'},
        { type: 'youtube', url: 'Fr8sFDADLhc', title: "blender"},
        { type: 'youtube', url: '7rOS_-JRPR0', title: "SuperVision"},
        { type: 'youtube', url: 'Qst1GHPG2oo', title: "Suis-moi"},
        { type: 'youtube', url: '1J8_J2mUvZU', title: "Immersive"},
        { type: 'youtube', url: 'weo86A0P76I', title: "ttfdf"},
        { type: 'youtube', url: 'Hb6OUEwCYPc', title: "sawmill"},
        { type: 'youtube', url: 'w-msBr0SvDU', title: "reel"},
        { type: 'youtube', url: 'd94D-ItDe8o', title: "BMR"},
        { type: 'youtube', url: 'P_ldPxA4BQ4', title: "Trapped"},
        { type: 'youtube', url: 'ToTaRDp75Mk', title: "LetItBurn"},
        { type: 'youtube', url: 'Sqhs2Dcvgvg', title: "LVDF"},
        { type: 'youtube', url: 'HgF5Qf3tiyE', title: "StoryTail"},
        { type: 'youtube', url: 'H0rvbYqONpg', title: "StageSIMAPTIC"},
        { type: 'youtube', url: 'e_RMhFvnhXE', title: "SpeedyDelivery"},
        { type: 'youtube', url: 'zfWhahruxG0', title: "Doga"},
        { type: 'youtube', url: 'QBIDHWLAJy4', title: "GTAV"},
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
  font-family: "Cal Sans", sans-serif;
  text-transform: uppercase;;
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

.reel {
  display: flex;
  flex-flow: column nowrap;
  width: 80%;
  height: 100vh; 
  justify-content: space-around;
  align-items: center;
  max-width: 1200px;
  margin-left: 20px;
  margin-right: 20px;
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
  margin-bottom: 10vh;
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

