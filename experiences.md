---
layout: default
---

# Expériences

 <div class="timeline">
  <div class="timeline-container left">
    <div class="content">
      <h2>2017</h2>
      <p>Codit</p>
    </div>
  </div>
  <div class="timeline-container left">
    <div class="content">
      <h2>Depuis Mars 2016</h2>
      <p>Caoba 
- Belleville (75) Automatisation des processus d’installations de systèmes
et sécurisation des services (
Bash
) - Stage de 6 mois et alternance en cours.</p>
    </div>
  </div>
  <div class="timeline-container right">
    <div class="content">
      <h2>2014-2018</h2>
      <p>Ingénierie du Logiciel, Titre Niveau 1 Certifié au RNCP
IN'TECH INFO, Groupe ESIEA, 74bis Avenue Maurice Thorez - Ivry-sur-Seine
(94)</p>
    </div>
  </div>
  <div class="timeline-container left">
    <div class="content">
      <h2>Avril-Juillet 2013</h2>
      <p>LISV
 - IUT Vélizy (78) Recherche en informatique : Programmation (Bash, C++)
et électronique (Arduino, Pandaboard) - Stage de 3 mois.</p>
    </div>
  </div>
  <div class="timeline-container left">
    <div class="content">
      <h2>2011-2012</h2>
      <p>BNP Paribas
 - Louveciennes (78) Service Informatique : Programmation (Java)
et maintenance - Apprentissage en alternance 1 an.</p>
    </div>
  </div>
     <div class="timeline-container right">
    <div class="content">
      <h2>2010-2013</h2>
      <p>DUT Informatique
IUT de Vélizy, Université de Versailles Saint-Quentin en Yvelines - Vélizy (78)</p>
    </div>
  </div>
    <div class="timeline-container right">
    <div class="content">
      <h2>Juillet 2010</h2>
      <p>Baccalauréat général 
Scientifique spécialité Mathématiques
Lycée Jacques Monod - Clamart (92)</p>
    </div>
  </div>
</div>

<style>
* {
  box-sizing: border-box;
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: #b5e853;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.timeline-container {
  padding: 10px 40px;
  position: relative;
  /* background-color: inherit; */
  width: 50%;
}

/* The circles on the timeline */
.timeline-container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #b5e853;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the timeline-container to the left */
.left {
  left: 0;
}

/* Place the timeline-container to the right */
.right {
  left: 50%;
}

/* Add arrows to the left timeline-container (pointing right) */
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid black;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent black;
}

/* Add arrows to the right timeline-container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid black;
  border-width: 10px 10px 10px 0;
  border-color: transparent black transparent transparent;
}

/* Fix the circle for timeline-containers on the right side */
.right::after {
  left: -16px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: black;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
/* Place the timelime to the left */
  .timeline::after {
    left: 31px;
  }

/* Full-width timeline-containers */
  .timeline-container {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

/* Make sure that all arrows are pointing leftwards */
  .timeline-container::before {
    left: 60px;
    border: medium solid black;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
  }

/* Make sure all circles are at the same spot */
  .left::after, .right::after {
    left: 15px;
  }

/* Make all right timeline-containers behave like the left ones */
  .right {
    left: 0%;
  }
}
</style>