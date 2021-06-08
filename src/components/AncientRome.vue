<template>
  <div>
    <div class="main">
  <h1>ANCIENT ROME</h1>
  <p>
    In historiography, <span>ancient Rome</span> is Roman civilization from the founding of the Italian city of Rome in the 8th century BC to the collapse of the Western Roman Empire in 5th century AD, encompassing the Roman Kingdom (753 BC - 509 BC), Roman Republic (509 BC - 27 BC) and Roman Empire (27 BC - 476 AD) untill the fall of the western empire. The civilization began as Italic settlement in the Italian Peninsula, traditionally dated to 753 BC, that grew into the city of Rome and which subseqently gave its name to the empire over which it ruled and to the widespread civilisation the empire developed.
  </p>

  <h1>WHAT IS ANCIENT ROME KNOWN FOR</h1>
  <P>
    The Romans were prodigious builder and expert civil engineers, and their thriving civilization produced and advances in technology, culture and architecture that remained unequaled for centuries.
    <br>
    Aqueducts. ... <br> Concrete. ... <br> Newspapers. ... <br> Bound Books. ... <br> Roads and highways. ... <br> Roman Arches. ... <br> The Julian Calender
  </P>
  <p>
      Rome was founded by two brothers nursed by a she-wolf. ... <br> <br> The Ancient Romans worsshipped a lot of different gods and goddesses. ... <br><br> Sometimes the Romans would flood the whole Colosseum or Circus Maximus for a boat battle. ... <br><br> Ancient Rome is underground. ... <br><br>Vestal virgins were chosen when they were less than ten-years old. ... 
    </p>
  </div>

  <div class="main">
    <h1>HOW DID ANCIENT ROME BEGIN</h1>
    <p>
      According to legend, <span>Rome</span> was founded in 753 BC by twins sons Romulus and Remus who were raised by she-wolf. During its twelve-century history, the <span>Roman</span> civilization shifted from a monarchy to an oligarchic republic to a immense empire. 
    </p>

    <h1>HOW MANY YEARS DID THE ROMAN EMPIRE LAST</h1>
    <p>
      The <span>Roman Empire was</span> one of the greatest and most influential civilizations i world history. It began in the city <span>of Rome</span> in 753 BC and lasted for well over 1000 <span>years</span>.
    </p>

    <h1>Roman Empire (27 BC - 476 AD)</h1>
    <p>
      The <span>Roman Empire was</span> founded when Augustus Caesar proclaimed himself the first emperor of Rome in 31 BC and came to an <span>end</span> with the fall of Constantinople in 1453CE.
    </p>
  </div>
  </div>
</template>

<script>
export default {
  name: 'AncientRome',
  props: {
    ancientrome: String
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
 animation: zoomin 1s linear 1;
 animation-delay: 2s;
 visibility: hidden;
 animation-fill-mode: forwards;
}
@keyframes zoomin {
  0%{
    transform: scale(0.5);
    visibility: visible;
  }
   100%{
    transform: scale(1);
    visibility: visible;
  }
}
h1 {
  font-family: 'Montserrat';
 font-size: 120%;
 color: blue;
}
p {
  font-family: 'Montserrat';
}
span {
  font-weight: bolder;
}
</style>
