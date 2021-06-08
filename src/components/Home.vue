<template>
  <div>
    <div id="body">
      <div class="sideright">
        <h2>Lecture Dates</h2>
        <p>11/07 - Lecture on Caesar</p>
        <p>11/14 - Lecture on Hannibal</p>
        <p>11/21 - Lecture on Alexander</p>
        <p>11/28 - Lecture on Napolean</p>
        <p>12/05 - Lecture on Scipio</p>
      </div>

      <div class="sideright2">
        <h2>Lecture Dates 2</h2>
        <p>11/07 - Lecture on Caesar</p>
        <p>11/14 - Lecture on Hannibal</p>
        <p>11/21 - Lecture on Alexander</p>
        <p>11/28 - Lecture on Napolean</p>
        <p>12/05 - Lecture on Scipio</p>
      </div>

      <div>
        <img class="imagesidebar" src="../assets/fivestar.png" />
      </div>

      <div class="main">
        <h1>HANNIBAL - THE BATTLE OF CANNAE</h1>
        <p>
          After the defeating the Romans at the battle of th lake Trasimene.
          Hannibal now moved his forces down south. There was panic the Rome and
          Quintus Fabius Maximus was appointed dictator to deal with Hannibal.
          Fabius, however, refused to meet Hannibalin the open field and this
          strategy became highly unpopular in the Rome. Romans were used to
          attacking, not hidding. The were forced to go the offensive after
          Hannibal positioned his forces between Rome and it's vital grain
          supply. This setup the epic Battle of Cannae. Here Hannibal defeated
          the Romans inflicting the worst single day defeat in Rome's history.
        </p>

        <h1>AFTERMATH OF THE BATTLE OF CANNAE</h1>
        <P>
          After the horrific defeat at the battleof cannae, the Romans
          reinstituted Fabius' avoidance strategy. The Romans no longer refused
          to meet Hannibalin head on collisions. Rather the Romans army kept
          watchful eye on Hannibal, but always at a close distance.
        </P>
        <p>
          The avoidance strategy worked but it took forword. It took almost two
          long decades to drive Hannibal out of Italy. And even then Hannibal
          was neverdefeated in Italy. The Romans adopting a tactic out of
          Hannibal's playbook, launched an attack against Carthage itself. This
          forced Hannibal to travel back to Africa to defend the city. Here he
          was defeated at the Battle of Zama.
        </p>
      </div>

      <div class="main">
        <h1>Ancient Egypt - THE Pharoah</h1>
        <p>
          The Pharoah was a living god. He was at the top of Ancient Egyptian
          society. The Pharoah was responsible for the well being of his people
          and was obligated to keep the order. He was all powerful and he spentn
          most of his time at the capital city of Memphis. Here he administrated
          control of both lower and upper Egypt.
        </p>

        <h1>The Tombs of the Pharoahs</h1>
        <p>
          The Pharoah spent most his life working on his tomb. The Pharoah's had
          this busy afterlife where they continued to control the universe after
          their death. The god Anubis assisted the pharoal in the mummfication
          process. After the pharoah died he traveled to the underworld using
          the Book of the Dead.
        </p>

        <h1>The Pyramids</h1>
        <p>
          The Pharoah spent most his life working on his tomb. The Pharoah's had
          this busy afterlife where they continued to control the universe after
          their death. The god Anubis assisted the pharoal in the mummfication
          process. After the pharoah died he traveled to the underworld using
          the Book of the Dead.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
body {
  margin: 0px;
  font-size: 14px;
}
.main {
  background-color: #e5e4d7;
  margin-left: 10px;
  margin-right: 360px;
  margin-top: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
  padding: 25px;
  font-size: 150%;
}
h1 {
  font-family: "Montserrat";
  font-size: 120%;
  color: #ce282e;
}
h2 {
  font-family: "Montserrat";
  font-size: 120%;
  color: darkblue;
}
p {
  font-family: "Montserrat";
}
.sideright {
  background-color: #e5e4d7;
  margin-left: 10px;
  margin-right: 10px;
  margin-top: 0px;
  width: 290px;
  margin-bottom: 10px;
  border-radius: 5px;
  padding: 25px;
  font-size: 130%;
  float: right;
  clear: right;
  animation: right 10s;
}
@keyframes right {
  0% {
    transform: translateX(2200px);
  }
  100% {
    transform: translateX(0px);
  }
}
.sideright2 {
  background-color: #e5e4d7;
  margin-left: 10px;
  margin-right: 10px;
  margin-top: 0px;
  width: 290px;
  margin-bottom: 10px;
  border-radius: 5px;
  padding: 25px;
  font-size: 130%;
  float: right;
  clear: right;
  animation: down 5s;
}
@keyframes down {
  0% {
    transform: translateY(-1200px);
  }
  100% {
    transform: translateY(0px);
  }
}
.imagesidebar {
  width: 340px;
  margin-left: 10px;
  margin-right: 10px;
  margin-top: 0px;
  margin-bottom: 10px;
  border-radius: 5px;
  float: right;
  clear: right;
  opacity: 1;
  transition: opacity 0.5s ease-in-out;
  transition: transform 1s 1s ease-in-out;
}
.imagesidebar:hover {
  opacity: 0.4;
  transform: rotate(180deg);
}
</style>
