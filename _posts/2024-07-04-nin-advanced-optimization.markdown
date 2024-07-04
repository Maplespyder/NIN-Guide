---
layout: post
author: Jackal Ka'tui @ Goblin
---

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

# Ninja Advanced Optimization

<hr>
<br>

## Extended Standard

Thanks to Kunai's Bane, our personal debuff is now <b class="pb">16.25 seconds</b> long. Meanwhile Dokuomori is <b class="pb">21 seconds</b>. While Dokumori's increase doesn't change much, Kunai's Bane's measly 0.48 second duration increase altered two things:

- JP Opener & Rotation is much easier to execute

- Introduction of <b class="pb">Extended Standard</b>

That is if Kunai's Bane is <b class="pb">late woven</b>, we can catch an additional GCD while also using x2 Raitons in our <b class="pb">even / 2-minute</b> windows.

<b style="color:red">WARNING:</b> It's pretty tight! The only drawback to trying this might be just drifting Kunai's Bane, but overall the gameplay is quite identical to standard. I recommend using <b class="pb">XIVAlexander</b> for ping induced animation locks and <b class="pb">Reaction</b> for FPS locking on all skills.

Another <b style="color:red">warning</b>, ideally this is done on 2.12 GCD to minimize Dokumori & Kunai's Bane drifting. 2.10 has natural drift and therefore you'll easily drift too far out of other player's buffs, and misalign Dokumori.

#### Example

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/extendedStandardEx1.png" style="max-width:800px" />
</div>

[Log Example](https://www.fflogs.com/reports/8CDgaWLVtBPy9bn4#fight=2&type=casts&view=events)

## JP Opener & Rotation

Since Kunai's Bane is <b class="pb">16.25 seconds</b> instead of 15.77s, JP Opener and Rotation is significantly easier than in Endwalker. Although <b class="pb">Extended Standard</b> is likely the better alternative unless replacing x1 Raiton with x1 GCD yields an extra Bhavacakra under Kunai's Bane.

If you're progging savage or ultimate, I highly recommend not doing this. It does make executing the 2-minute window tighter due to drifting Kassatsu into our Kunai's Bane window. Furthermore, alignment may be difficult to handle as we'll be placing x1 Raiton between Dokumori and Kunai's Bane.

In short, the theory behind the JP Opener & Rotation involves replacing x1 Raiton (740p) with x2 GCDs (x1 Raiju and x1 combo/PK). These x2 GCDs are always higher than Raiton. Additionally, there's an extra chance to gain an additional bhavacakra under Kunai's Bane. <b class="pb">Kunai's Bane must be late woven to make this work.</b>

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/jpOpener.png" style="max-width:800px" alt="jpOpener"/>
</div>

#### General Tips

- Late weave <b>Kunai's Bane</b> as late as possible without clipping, even after a Ninjutsu.
- If Bunshin is active: Priotize <b>Forked Raiju</b> over <b>Fleeting Raiju</b> as the final GCD in Kunai's Bane. Due to Forked Raiju's quicker damage application, our bunshin will prepare damage that much quicker.

#### Rotation

Much like the opener, similar logic will be applied to every 2-minute window. That is, removing a Raiton from Kunai's Bane and replacing it with x2 GCDs.

There is also an additional benefit when Bunshin is active. In addition to the 2 extra GCDs under Kunai's Bane, these GCDs also will have the damage bonus. For example, if you replaced Raiton (700p) with Raiju + Gust (600 + 380), that gain could become 1300p vs 700p under Kunai.

#### Examples

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/jpEx1.png" style="max-width:800px" alt="jpOpener"/>
</div>
- Dokimori being late woven catches a 5th GCD, else it would end after the last Raiju.
- Naturally, Kunai's Bane being used after Raiton automatically catches the 4th GCD.

<div style="text-align: center;">
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/jpEx2.png" style="max-width:800px" alt="jpOpener"/>
</div>
- Alternative method by using Phantom Kamaitachi between Raiton and Kunai's Bane. 
- Ensure Kunai's Bane is a late weave here.
