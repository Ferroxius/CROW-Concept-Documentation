# Combat concepts
> Any relevant concepts or ideas related specifically to COMBAT should go here

- [Combat concepts](#combat-concepts)
  - [Resources](#resources)
    - [Vitality](#vitality)
    - [Toxicity](#toxicity)
    - [Stamina](#stamina)
    - [Poise](#poise)
    - [Adrenaline](#adrenaline)
  - [Status Effects](#status-effects)
  - [Signs](#signs)
    - [Quen](#quen)
    - [Axii](#axii)
    - [Aard](#aard)
    - [Igni](#igni)
    - [Yrden](#yrden)
  - [Movement](#movement)
    - [Mobility](#mobility)
    - [Dodging](#dodging)
    - [Parrying](#parrying)
    - [Lock on](#lock-on)
  - [Combat dynamics](#combat-dynamics)

---

## Resources
### Vitality
Is at a static value and can only be boosted temporarily or through items like mutagens
Geralt has passive albeit slow vitality regeneration which can be boosted through consuming food and drink as well as potions like swallow

### Toxicity
Toxicity is still applied as a static amount to your total toxicity value. However, in combat your toxicity decrease per second is minimal unless your adrenaline is high giving you incentive to keep it high

Potions add toxicity, however they have a “metabolism period”, during this brief period drinking any more potions will add an additional amount of toxicity on top of the toxicity added by the next potion. This is to prevent spam drinking multiple potions and decoctions, be considerate now

If you add more toxicity when already near full toxicity then any toxicity added past the threshold will contribute poison damage to Geralt meaning while you aren’t technically limited by how many potions you can take you will die if you try going too hard

The poison status effect can build toxicity

### Stamina
Stamina remains infinite as usual and is the basis for which signs are cast. Much like vanilla each cast drains the bar entirely. However, you can cast the sign again at half stamina without waiting for the bar to refill but the sign intensity on the next cast will be lowered

### Poise
A special resource that replaces the exp bar and governs parrying. Every time you perform a normal parry you will lose some poise. However, if you parry just before an enemy strikes you can “perfect parry” them which will not cost any poise
If your poise drops to zero you will become poisebroken and will be briefly stunned, however if you continue to perfect parry you will never be poisebroken even if you are out of poise. Poise will begin to regenerate if Geralt is not attacking or dodging or it can regenerate quickly if Geralt holds down the parry key

Enemies too have poise and are susceptible to being poisebroken, if they are poisebroken Geralt can perform a finisher instantly killing them. On larger enemies though where this is not possible it simply takes a chunk of their health away
Humans and Monsters have varying degrees of poise and health, typically enemies with low health will have high poise and enemies with high health will have low poise. Enemies with high poise though will typically be able to parry your attacks so the focus will shift depending on your enemy

### Adrenaline
A resource that acts as a passive booster to your other values. Higher adrenaline will result in higher toxicity degen, higher health regen and higher stamina regen
Adrenaline doesn’t naturally build on its own and can only be built up by attacking and doging (Perfect dodges award more adrenaline). However if you remain inactive for a time period adrenaline will start to drop back down to zero and you will lose your boosts

## Status Effects
Geralt can be inflicted with various status effects that hinder him in combat. The two main ones of focus are bleed and poison

Bleed stacks up to 10 and can be applied through a number of means. This can quickly drain your health if you are not ready. To counteract this you should use craftable bandages 

Poison stacks up to 10 and while it has a small amount of health damage it primarily serves to fill your toxicity meter messing with your toxicity. If it goes over your toxicity limit it will start dealing tick damage to you

---
## Signs
### Quen
Instead of serving as a means of protection from physical attacks, quen now serves as a form of physical protection against elemental attacks e.g. lifedrain, fire attacks, ice attacks. Any form of elemental damage is shielded when passive quen is activated. However, quen does nothing to protect against physical attacks and as such getting hit by a physical attack will deal full damage to you and break the shield.
Active quen shield is the opposite in that it defends well against physical attacks but less so against elemental attacks. It also hampers your movement meaning you won’t be as mobile and you cannot do anything else while holding it
Quen can also be used to counter opponents by quick casting it just before an opponent strikes. This doesn’t deal any damage but can apply knockback/knockdown to the enemy

### Axii
Normal Axii like normal stuns an enemy for a period of time
Puppet functions like normal except your movement speed is not hampered when casting as to allow you to move and not get hit by an enemy interrupting the cast

### Aard
Can cause knockback/knockdown on enemies. Particularly useful on flying creatures

### Igni
Can easily set enemies on fire leading them vulnerable to several hits. Good against small groups or single targets to open them up and whittle them down

### Yrden
Similar in design to EE, enemies that stay within the normal Yrden circle will become snared
Warding Glyph in design to EE zaps enemies if they try to hit you and can also destroy projectiles before they hit you

---
## Movement
### Mobility

Geralts mobility will be sharply increased to give him better means of getting around in a fight. Enemies though can also be fast

### Dodging
Dodging in the base game is a bit too easy since the i-frames are a bit too generous
As such timing will now need to be employed and is designed around dodges and “perfect dodges”. If you dodge just before an enemy hits you, you will take no damage as you have perfectly dodged. If you dodge any time before or after this you will take chip damage which is less than if you didn’t dodge at all but is still important to factor

### Parrying
Geralt possesses the ability to parry incoming direct attacks from most monsters and all humans. He cannot parry elemental attacks or certain unparryable attacks in which case he should attempt to dodge these. These unparryable attacks will be visually and audibly shown so you know when they occur

### Lock on
Lock on will focus Geralts attacks to a specific enemy and can be changed between enemies. The camera will also lock onto a specific enemy

## Combat dynamics
With no stamina cost (or any resource consumption) on fast nor heavy attacks and to ensure a dynamic and varied combat gameplay the default regeneration of the player's stamina is slowed down. Then for each attack the player lands a stacking effect is granted, heavy attacks grant more stacks of the effect than fast attacks. That effects expires one stack at a time after a few seconds, and gives a stacking bonus stamina regeneration.

Taking damage also causes the player to lose some of its stacks (if any) depending on the severity of the hit.

The bonus stamina regeneration over time gained from landing attacks, plus the somewhat slower (compared to vanilla) passive means that in order to cast signs frequently the player must fight aggressively while avoiding hits.

The short nature of the buff and the fact it stacks but expires only one stack at a time puts even more importance to heavy attacks since they grant multiple stacks at once. Heavy attacks, while harder to land, will offer a way to quickly gain a steady stamina regeneration for a decent amount of time. The fast attacks on the other hand will be perfect to maintain that regeneration. During the times where not getting hit is most important, the effect and its stacks will naturally expire offering another opportunity to land some more heavy attacks
