---
layout: post
author: Jackal Ka'tui @ Goblin
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-H8ES4HMSPV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-H8ES4HMSPV');
</script>

<style>


body {
  background: #0d1117;
  color: white;
}

.pb {
    color: #c92664;
}

.sb {
    color: white;
}

a { 
  font-weight: bold;
}

code {
  background: black !important;
}

.highlight {
  background: black !important;
  color: white;
}

/* tr {
  background: #161b22 !important;
  color: white;
} */

tbody tr:nth-child(odd) {
    background-color: #0d1117;
    color: white;
}

tbody tr:nth-child(even) {
    background-color: #161b22;
    color: white;

}

th {
    background-color: #0e1114 !important;
    color: white;
}



table {
  background: black;
    display: block;
    max-width: fit-content;
    margin: 0 auto;
    border: 2px solid #2a2a2a;
    border-collapse: collapse;
    width: 100%;
}
</style>

<hr>
<br>

For both options below, I recommend using <b class="pb">XIVAlexander</b> for reducing ping induced animation locks and <b class="pb">Reaction</b> for FPS locking on all skills.

These options are often rather slight gains (20-50rdps) over standard, so it's not necessary to do this but for anyone wishing to milk any extra DPS they can.

## Extended Standard

<hr>
<br>

Thanks to Kunai's Bane, our personal debuff is now <b class="pb">16.25 seconds</b> long. Meanwhile Dokuomori is <b class="pb">21 seconds</b>. While Dokumori's increase doesn't change much, Kunai's Bane's measly 0.48 second duration increase altered two things:

- JP Opener & Rotation is much easier to execute

- Introduction of <b class="pb">Extended Standard</b>

That is if Kunai's Bane is <b class="pb">late woven</b>, we can catch an additional GCD while also using x2 Raitons in our <b class="pb">even / 2-minute</b> windows.

<b style="color:red">WARNING:</b> It's pretty tight! The only drawback to trying this might be just drifting Kunai's Bane, but overall the gameplay is quite identical to standard.

#### Example

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/extendedStandardEx1.png" style="max-width:800px; border: 1px solid white;" />
</div>

[Log Example](https://www.fflogs.com/reports/8CDgaWLVtBPy9bn4#fight=2&type=casts&view=events)

#### Openers

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/extStand4th.png" style="max-width:800px; border: 1px solid white;" />
</div>

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/extStand3rd.png" style="max-width:800px; border: 1px solid white;" />
</div>

#### General Tips

- Prioritize not putting Phantom Kamaitachi as the last GCD under Kunai, due to it preparing on the boss later due to being executed by the pet.

## JP Opener & Rotation

<hr>
<br>

Since Kunai's Bane is <b class="pb">16.25 seconds</b> instead of 15.77s, JP Opener and Rotation is significantly easier than in Endwalker. It should be easier to fit in the extra GCD compared to Extended Standard, albeit a bit more awkward due to the Raiton before Kunai's Bane.

If you're progging savage or ultimate, I highly recommend not doing this. It does make executing the 2-minute window tighter due to drifting Kassatsu into our Kunai's Bane window. Furthermore, alignment may be difficult to handle as we'll be placing x1 Raiton between Dokumori and Kunai's Bane.

In short, the theory behind the JP Opener & Rotation involves replacing x1 Raiton (740p) with x2 GCDs (x1 Raiju and x1 combo/PK). These x2 GCDs are always higher than Raiton. Additionally, there's an extra chance to gain an additional bhavacakra under Kunai's Bane. <b class="pb">Kunai's Bane must be late woven to make this work.</b>

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/jpOpener.png" style="max-width:800px; border: 1px solid white;" alt="jpOpener"/>
</div>

#### General Tips

- Late weave <b>Kunai's Bane</b> as late as possible without clipping.
- Prioritize not putting Phantom Kamaitachi as the last GCD under Kunai, due to it preparing on the boss later due to being executed by the pet.

#### Rotation

Much like the opener, similar logic will be applied to every 2-minute window. That is, removing a Raiton from Kunai's Bane and replacing it with x2 GCDs.

There is also an additional benefit when Bunshin is active. In addition to the 2 extra GCDs under Kunai's Bane, these GCDs also will have the damage bonus. For example, if you replaced Raiton (740p) with Raiju + Gust (640 + 380), that gain could become 1314p vs 740p under Kunai.

#### Examples

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/jpEx1.png" style="max-width:800px; border: 1px solid white;" alt="example"/>
</div>
- Dokumori being late woven catches a 5th GCD, else it would end after the last Raiju.
- Naturally, Kunai's Bane being used after Raiton automatically catches the 4th GCD.

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/jpEx2.png" style="max-width:800px; border: 1px solid white;" alt="example"/>
</div>
- Alternative method by using Phantom Kamaitachi between Raiton and Kunai's Bane. 
- Ensure Kunai's Bane is a late weave here.
