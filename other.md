---
layout: default
title: Others
---

<style>
  .spiral-bg {
    position: fixed;
    right: -60px;
    bottom: -60px;
    width: 520px;
    max-width: 70vw;
    height: auto;
    pointer-events: none;
    z-index: 0;
    opacity: 0.4;
    /* Light mode: Invert the black JPG to a white background with dark lines, then multiply to make the white transparent */
    filter: invert(1);
    mix-blend-mode: multiply;
    transition: opacity 0.3s, filter 0.3s;
  }

  html.dark .spiral-bg {
    /* Dark mode: Keep the black background with light lines, use screen to make the black transparent */
    filter: none;
    mix-blend-mode: screen;
    opacity: 0.3;
  }

  main {
    position: relative;
    z-index: 1;
  }
</style>

## Things I like

Reading novels and manga, watching films and anime, folding origami.

<img class="spiral-bg" src="images/background_spiral.jpg" alt="" aria-hidden="true">