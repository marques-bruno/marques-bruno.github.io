---
title: A silicon liver phantom
layout: post
---
<!-- Text stuff -->
<p>Alright! first post here. Busy week at <b>MIMESIS</b>! We started to look seriously into how to build a silicon model of a human liver that would accurately mimmick the opacity of human liver tissues under xrays. For those who don't know the context of the project and are interested in the <i>why</i>, you can take a look at the <strong>IHU</strong> project I'm currently working on <a href="https://mimesis.inria.fr/projects/endovascular-surgery-fusion/">HERE</a>.<br/>
  <br/>

  So let's take a look at the problem:
  <h3>We want:</h3>
  <ul>
    <li>a liver model that looks like a liver;</li>
    <li>a model that can be deformed, preferably in a mecanically similar manner as an actual liver;</li>
    <li>Radio-absorbing materials so we can see it in a CAT scan for instance;</li>
    <li>Internal structures (tumors, blood vessels etc.) that would be visible with xray</li>
    <li>materials that preferably don't degrade with time</li>
  </ul>

  Great! So the first pick for the material that comes to mind is...: silicone! Silicone is a very elastic material, extremely stable chemically, and can easily be casted into whatever shape you want, as long as you can get your hands on a mold...<br/>
  <br/>
  There are different types and brands of silicones, but at work, we already used the <a href="https://www.smooth-on.com/products/ecoflex-00-20/">Ecoflex 00-20 from Smooth-On</a> that is very soft, and the <a href="https://www.smooth-on.com/products/mold-max-10/">Mold Max 10</a> that is much harder.<br/>
  Since it's an early prototype, and we happen to have some Mold Max hanging around, we used this for a start.<br/>
  <a href="#" class="image smallright"><img src="{{ 'assets/images/siliconliver/BaSO4_concentration.png' | relative_url }}" alt="various concentrations of Barium sulfate inside silicone samples" title="various concentrations of Barium sulfate inside silicone samples"/></a><br/>
  Now for the radio-absorption, we need to be able to play with the radio-opacity of the silicone. A colleague of mine got the idea of using Barium sulfate (BaSO4) (which is used clinically as a contrast agent) and mix it with the silicone.<br/>
  We made small silicone samples, with different concentrations of barium sulfate, and compared it to CT images of a human liver. 5% of BaSO4 seems to be what got us the closest.<br/><br/>
  <a href="#" class="image smallleft"><img src="{{ 'assets/images/siliconliver/mini_mold.png' | relative_url }}" alt="a miniature prototype of the final PVA mold. vasculature can be seen inside"/></a>
  Finally, we need to create a mold for our liver, and we need to figure out how to cast the blood vessels inside. My colleague Fabian got the idea to 3D print a shell in PVA (a water-soluble material) that would contain the blood vessels, and to then cast the silicone in that shell. PVA is commonly used in multi-material 3D printers to create water-soluble support materials, and we happen to have some PVA filament hanging around at IHU.<br/><br/><br/><br/><br/>

  So! all this looks pretty promising. Next, we are now printing the complete mold in PVA. The idea is that once the silicone is cured inside the mold, we can dissolve it, vessels included. Once dissolved we can inject silicone with a higher amount of BaSO4 in the cavities, which would give us a good-looking liver in the CT!<br/>
<br/>
  I'll come back with some results soon, hopefully! :)
  
