---
layout: project
type: project
image: images/micromouse.jpg
title: Micromouse
permalink: projects/hero-feto
# All dates must be YYYY-MM-DD format!
date: 2018-07-01
labels:
  - Unity
  - C#
summary: Hero feto.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
</div>

Jogo hero feto

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

Saiba mais no link [Website](http://oxentegames.com.br/hero-feto.html).



