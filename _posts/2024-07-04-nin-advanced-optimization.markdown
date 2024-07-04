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
<img src="https://maplespyder.github.io/NIN-Guide/assets/images/extendedStandardEx1.png" style="max-width:700px" />
</div>

[Log Example](https://www.fflogs.com/reports/8CDgaWLVtBPy9bn4#fight=2&type=casts&view=events)

## JP Opener & Rotation

This is a very cursed section and I recommend you skip this unless you're looking to gamble for some pennies. You trying to prog savage or ultimate? Don't even bother. I promise it's not worth it. It's more suited for hyperoptimizers, such as speedrunners or parsers.

While it is recommended to use the 4th GCD Trick Opener, but for those who know what they're signing up for, doing the JP opener is a higher potency alternative. The theory is replacing Raiton (700p) with x2 GCDs (x1 Raiju and 1 combo/PK). The x2 GCDs is always higher than Raiton.

Executing this opener + rotation, however, is only a 30 RDPS gain in a 6m fight. And swiftly becomes a loss if done incorrectly.

<b style="color:red">WARNING:</b> This is <b>incredibly</b> easy to mess up and only gets worse the higher your ping is. Landing the last GCD in Kunai's Bane is as close as 0.10s, and a Bunshin executed GCD is even tighter.

While NoClippy or XIVAlexander can help, playing above 100ms is more trouble than it is worth. Mostly due to <b>Hyosho Ranryu</b> having an unavoidable clip based on your ping.

[I mean come on...](https://youtu.be/mnrTRu0uaGM?si=de5KdWhbxD0qngrO)

```
 Hyosho / Goka recast = 1.50 + ( PING * 2 / 1000)

 //at 70ms, my Hyosho's recast is 1.64s.
```

There is an <b class="pb">exception</b> though. If you miss the last GCD in Kunai's Bane due to your ping / misplay, it's sometimes still better than standard. If Bunshin is active, replacing Raiton with x1 Raiju (600 + 160 > 700). But in return, you did sort of drift Kassatsu into your Kunai's Bane... so kind of a hassle.

Anyway...

<div style="text-align: center;">
<img src="https://i.imgur.com/Eka0RdS.png" style="max-width:700px" alt="jpOpener"/>
</div>

#### General Tips

- Consider having 20ms or below ping.
- Late weave <b>Kunai's Bane</b> as late as possible without clipping, even after a Ninjutsu.
- Avoid using Phantom Kamaitachi as the last GCD in Kunai's Bane.
- If Bunshin is active: Priotize <b>Forked Raiju</b> over <b>Fleeting Raiju</b> as the final GCD in Kunai's Bane. Due to Forked Raiju's quicker damage application, our bunshin will prepare damage that much quicker.

#### Rotation

Much like the opener, similar logic will be applied to every 2-minute window. That is, removing a Raiton from Kunai's Bane and replacing it with x2 GCDs.

There is also an additional benefit when Bunshin is active. In addition to the 2 extra GCDs under Kunai's Bane, these GCDs also will have the damage bonus. For example, if you replaced Raiton (700p) with Raiju + Gust (600 + 380), that gain could become 1300p vs 700p under Kunai.

#### Examples

...
