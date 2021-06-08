<template>
  <div>
      <div class="main">
  <h1>ANCIENT GREECE</h1>
  <p>
    Ancient Greece was a civilization belonging to a period of Greek history from the Greek Dark ages of the 12th-9th centuries BC to the end of antiquity. This era was immediately followed by the Early Middle Ages and the Byzantine period. <br> <br>
    Beginning date: 800 BC
  </p>

  <h1>WHAT IS ANCIENT GREECE MOST KNOWN FOR?</h1>
  <P>
    The <span>Greek</span> made important contributions to philosophy, mathematics, astronomy and medicine. ... The <span>Greeks</span> were <span>known for</span> their sophisticated sculpture and architecture. <span>Greek</span> culture influenced the Roman Empire and many other civilizations, and it continues to influence modern cultures today.
  </P>

  <h1>TOP 10 FACTS ABOU THE ANCIENT GREECE</h1>
  <p>
    * Ancient Greece had lots of city state. ...
    <br>
    <br>
    * Marathons came from Ancient Greek times! ...
    <br>
    <br>
    * About one third of the Ancient Greeks were slaves. ...
    <br>
    <br>
    * The juries were huge! ...
    <br>
    <br>
    * They worship many Gods and Goddesses. ...
    <br>
    <br>
    * 12 of the Gods and Goddesses lived on mount Olympus. ...
    <br> <br>
    * Greeks called themselves 'Hellenes' <br> <br>
    * The Romans copied the Greeks!
  </p>
  </div>

  <div class="main">
    <h1>THE FUN FACT ABOUT ANCIENT GREECE</h1>
    <p>
      The <span>Greeks</span> often ate dinner while lying on their sides. They invented the yo-yo which is considered the 2nd oldest toy in the world after the doll. About one third of the population of some city-states were slaves.
    </p>

    <h1>OVERVIEW AND TIMELINE OF <span>ANCIENT GREEK</span> CIVILIZATION</h1>
    <p>
      The civilization of <span>Ancient Greece</span> emerged into the light of <span>history</span> in the 8th century BC. <br> Normally it is regarded as coming to an end when <span>Greece</span> fell to the Romans, in 146 BC.
    </p>

    <h1>LIFE FOR A CHILD IN ANCIENT GREECE</h1>
    <p>
      In some <span>Greek</span> cities, <span>children</span> were wrapped up in clothes untill they were about two years old to insure straight and strong limbs. <br> Other city-states, such as Sparta, did not do this to their children..<span>Children</span> spent the majority of their time with their mother. They stayed in the woman's part of the house.
    </p>
  </div>
    </div>
</template>

<script>
export default {
  name: 'AncientGrece',
  props: {
    ancientgreece: String
  }
}
</script>

<style scoped>
.main {
 background-color: #e5e4d7;
 margin-left: 10px;
 margin-right: 10px;
 margin-top: 10px;
 margin-bottom: 10px;
 border-radius: 5px;
 padding: 20px;
 font-size: 150%;
 animation: fade 10s 0.2s forwards ease-out
}
@keyframes fade {
 0% {
  opacity: 0;
  transform: translateX(-4rem);
 }
 100%{
  opacity: 1;
  transform: none;
 }
}
h1 {
  font-family: 'Montserrat';
 font-size: 120%;
 color: green;
}
p {
  font-family: 'Montserrat';
}
span {
  font-weight: bolder;
}
</style>
