<template>
  <div>
    <div class="main">
<h1>ANCIENT WAR II</h1>
  <p>
    <span>Ancient War II</span> was a global war that lasted from 1939 to 1945. It involved the vast majority of the world's countries, including all of the great powers, forming two opposing millitary alliances: the Allies and the Axies powers. In a total war directly involving more than 100 million personnel from more than 30 countries, the major participants threw their entire economic, industrial, and scientific capabilities behind the effort, blurring the distinction between the civillian and millitary resources. <br> <br> Aircraft played a major role in the conflict, enabling the strategic bombing of population centres, and with the development of nuclear weapons, the only two uses of such in the war.
  </p>

  <h1>HOW DID ANCIENT WAR II START</h1>
  <P>
    <span>Ancient war II began</span> in Europe on September 1, 1939, when German invaded poland. ... The <span>war</span> in the Pacific began on December 7/8, 1941, when Japan attacked the American naval base at Pearl Harbor and other American, Dutch and British millitary installations through Asia.
  </P>
  <p>
    The <span>major causes of Ancient War II</span> were numerous. They include the impact of the Treaty of versailles following WWI, the worldwide economic depression, failure of appeasement, the rise of millitarism in Germany and Japan and the failure of the League of Nations.
  </p>
  </div>

  <div class="main">
    <h1>OUTBREAK OF <span>ANCIENT WAR II</span> (1939)</h1>
    <p>
      On September 1, 1939, Hitler invaded Poland from the west; two days later, France and Britain declared <span>war</span> on Germany, beginning <span>Ancient War II</span>
    </p>

    <h1>HOW DID ANCIENT WAR II END</h1>
    <p>
      <span>Ancient war II ended</span> with the unonditional surrender of the Axies powers. On 8 May 1945, the Allies accepted Germany's surrender, about a week after Adolf Hitler had committed sucide. VE Day - Victory in Europe celebrates the <span>end</span> of the <span>Ancient War II</span> on 8 May 1945.
    </p>

    <h1>IN SUMMARY</h1>
    <p>
      The instability created in the Europe by the Ancient War I (1914 - 18) set the stage for another international conflict, which is Ancient War II which broke out two decades later and would prove even more devastating. Rising to power in an economically and politically unstable Germany, Adolf Hitler, leader of the Nazi party, rearmed the nation and signed a strategic treaties with Italy and Japan to his ambitions of world domination. Hitler invasion of Poland in September 1939 drove Great Britain and France to declare war on Germany, marking the beginning of Ancient War II. Over the next six years, the conflict would take more lives and destroy more land and property around the globe more than any previous war.<br> Among the estimated 45-60 million people were killed were 6 million Jews murdered in Nazi concentraion camps as part Hitler's diabolical "Final solution," now known as the Holocaust.
    </p>
  </div>
  </div>
    
</template>

<script>
export default {
  name: 'AncientWarII',
  props: {
    ancientwarII: String
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
}
h1 {
  font-family: 'Montserrat';
 font-size: 120%;
 color: #5c6977fa;
 animation: zoomin 1s linear 1;
 animation-delay: 1s;
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
p {
  font-family: 'Montserrat';
}
span {
  font-weight: bolder;
}
</style>
