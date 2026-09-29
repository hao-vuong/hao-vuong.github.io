---
layout: page
title: more
permalink: /more/
description: 
nav: true
nav_order: 3
---

<div style="text-align: center; margin-bottom: 50px;">
  <h4 style="color: var(--global-theme-color); font-style: italic;">
    <b>I balance robotic proprioception with street proprioception!</b>
  </h4>
</div>

<div class="zigzag-gallery">
  <img src="/assets/img/bot2.jpg" alt="art 1">
  <img src="/assets/img/graff6.jpg" alt="art 2">
  <img src="/assets/img/graff9.jpg" alt="art 3">
  <img src="/assets/img/bot3.jpg" alt="art 4">
  <img src="/assets/img/graff1.jpg" alt="art 5">
  <img src="/assets/img/graff12.jpg" alt="art 6">
  <img src="/assets/img/graff10.jpg" alt="art 7">
  <img src="/assets/img/graff2.jpg" alt="art 8">
  <img src="/assets/img/bot1.jpg" alt="art 9">
  <img src="/assets/img/graff7.jpg" alt="art 10">
  <img src="/assets/img/graff11.jpg" alt="art 11">
</div>

<style>
  .post-header {
  display: none;
  }

  .zigzag-gallery {
    display: flex;
    flex-direction: column;
    padding: 20px 0;
  }
  
  .zigzag-gallery img {
    width: 65%;
    max-width: 450px;
    position: relative;
    border: 8px solid var(--global-card-bg-color); 
    box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    border-radius: 12px;
    transition: transform 0.2s ease;
  }
  
  .zigzag-gallery img:not(:first-child) {
    margin-top: -15%; 
  }
  
  .zigzag-gallery img:nth-child(odd) {
    align-self: flex-start;
    margin-left: 5%;
  }
  
  .zigzag-gallery img:nth-child(even) {
    align-self: flex-end;
    margin-right: 5%;
  }
  
  .zigzag-gallery img:hover {
    z-index: 10;
    transform: scale(1.02);
  }
</style>