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
</style>

<div class="robocup-section">
  <img src="/robocup.jpeg" alt="RoboCup">
  <div class="text-content">
    <h2 style="margin-top: 0; font-size: 1.5rem;">¿Que es RoboCup?</h2>
    <p style="font-size: 0.9rem;">Robocup es una competencia internacional que se lleva a cabo anualmente desde el 1997 en diferentes países, con robots autónomos para fomentar el desarrollo, investigación, educación sobre inteligencia artificial. Entre todas las categorías que ofrece la competencia, Sysmic compite en la Small Size League, que consiste en la investigación usando el fútbol como plataforma de desarrollo, teniendo como objetivo que al 2050 un equipo de robots logre vencer a los campeones del mundial de la FIFA de ese año.</p>
  </div>
</div>
