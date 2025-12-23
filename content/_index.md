---
title: "Sysmic Robotics"
description: "Sysmic es una organización estudiantil enfocada a la investigación y desarrollo de robots autónomos capaces de jugar fútbol en la competencia mundial RoboCup."
featured_image: "/cover.jpg"
---

<style>
  .robocup-section {
    display: flex;
    align-items: center;
    gap: 2rem;
    margin: 2rem auto;
    width: 80vw;
    max-width: 1400px;
    position: relative;
    left: 50%;
    transform: translateX(-50%);
  }
  .robocup-section img {
    width: 55%;
    height: auto;
    flex-shrink: 0;
    object-fit: cover;
  }
  .robocup-section .text-content {
    flex: 1;
    min-width: 0;
  }
  @media (max-width: 768px) {
    .robocup-section {
      flex-direction: column;
      width: 90vw;
    }
    .robocup-section img {
      width: 100%;
    }
  }
  .liga-section {
    display: flex;
    align-items: center;
    gap: 2rem;
    margin: 2rem auto;
    width: 80vw;
    max-width: 1400px;
    position: relative;
    left: 50%;
    transform: translateX(-50%);
  }
  .liga-section img {
    width: 55%;
    height: auto;
    flex-shrink: 0;
    object-fit: cover;
    order: 2;
  }
  .liga-section .text-content {
    flex: 1;
    min-width: 0;
    order: 1;
  }
  @media (max-width: 768px) {
    .liga-section {
      flex-direction: column;
      width: 90vw;
    }
    .liga-section img {
      width: 100%;
      order: 1;
    }
    .liga-section .text-content {
      order: 2;
    }
  }
</style>

<div class="robocup-section">
  <img src="/robocup image.jpg" alt="RoboCup">
  <div class="text-content">
    <h2 style="margin-top: 0; font-size: 1.5rem;">¿Que es RoboCup?</h2>
    <p style="font-size: 0.9rem;">Robocup es una competencia internacional que se lleva a cabo anualmente desde el 1997 en diferentes países, con robots autónomos para fomentar el desarrollo, investigación, educación sobre inteligencia artificial. Entre todas las categorías que ofrece la competencia, Sysmic compite en la Small Size League, que consiste en la investigación usando el fútbol como plataforma de desarrollo, teniendo como objetivo que al 2050 un equipo de robots logre vencer a los campeones del mundial de la FIFA de ese año.</p>
  </div>
</div>

<div class="liga-section">
  <div class="text-content">
    <h2 style="margin-top: 0; font-size: 1.5rem;">Nuestra Liga</h2>
    <p style="font-size: 0.9rem;">La RoboCup Small Size League es una de las ligas de fútbol más antiguas de RoboCup. Se centra en la coordinación y el control inteligente de múltiples agentes en un entorno altamente dinámico. Actualmente, los equipos compiten en partidos de fútbol de 6 contra 6 (en la división B) con una pelota de golf naranja. Los robots son construidos por los equipos y deben cumplir con ciertas dimensiones y restricciones, según lo definido en las reglas. Todos los objetos en el campo son rastreados por un sistema de visión central, llamado SSL-Vision, mantenido por la comunidad SSL. Los ordenadores externos de cada equipo se utilizan para el procesamiento necesario para la coordinación y el control de los robots. La comunicación es inalámbrica y utiliza unidades comerciales de transmisión/recepción de radio dedicadas. En esta liga se busca la innovación en las áreas de locomoción, control, coordinación y toma de decisiones. </p>
  </div>
  <img src="/seccion_ssl.jpg" alt="Small Size League">
</div>