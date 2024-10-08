---
title: Game of Life
artist: Tim Wei
publishDate: 2022-02-02 00:00:00
img: https://storage.googleapis.com/profolio_media/public/assets/game/done.jpg
img_alt: flower
photo: Took in museum
size: 1.5*1.5*0.5 m
link: https://www.timwei.net/gameoflife
artistSite: https://www.timwei.net/
description: |
  Game of Life is an installation by artist Tim Wei comprising 169 cubes. These cubes move forward and backward following the
  rules of Conway's famous "Game of Life." Audience members can touch the cubes to affect their state. I utilized matrix scanning and
  MOSFETs to manage the 169 sensor inputs. The cubes are moved using pneumatic pressure.
tags:
  - Contorl System
  - PCB Design
---

<style>
  @media (max-width: 900px) {

     h3 {
      font-size: var(--text-lg);
    }
  }
</style>

This work, created by artist Tim Wei, commemorates the famous mathematician John Horton Conway. It features 169 cubes arranged in a square, following the rules of Conway's Game of Life. The cubes continuously move back and forth according to the states, synchronized with sounds designed by the artist. The audience can interact with the installation by touching the pixels, altering their state (alive or dead) and triggering a chain reaction of changes.

Technically, the challenging aspect is that all 169 cubes are equipped with sensors, which require a large number of input/output (IO) connections—a uncommon requirement. To address this, I used MOSFETs and matrix scanning to reduce the number of IO connections from 169 to 26. Then all the sensors can be detected within one microcontroller.

<div class="gallery" style="    margin-top:100px;">

<div class="height withTitle" >
<span class="imgTitle">PCB Design</span>
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/pcb.jpg">

</div>

<div class="height withTitle" >
<span class="imgTitle">PCB Design</span>
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/brd.jpg">

</div>

<div class="height withTitle" >
<span class="imgTitle">Mosfet Matrix</span>
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/pcb2.jpg">

</div>

<div class="height withTitle" >
<span class="imgTitle">Mechanical Structure</span>
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/nake.jpg">

</div>
<div class="height withTitle" >
<span class="imgTitle">Wiring</span>
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/wire2.jpg">

</div>
<div class="height withTitle" >
<span class="imgTitle">In Progress</span>
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/work.jpg">

</div>

<div class="height" >
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/close.jpg">
</div>

<div class="height withTitle" >
<span class="imgTitle">Touch Sensing</span>
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/touch.gif">
</div>

<div class="height " >
<img style=""src="https://storage.googleapis.com/profolio_media/public/assets/game/show.gif">
</div>

</div>
