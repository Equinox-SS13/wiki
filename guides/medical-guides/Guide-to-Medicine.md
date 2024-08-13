---
title: Guide to Medicine
description: All you need to start out as a doctor or field medic.
published: false
date: 2024-08-13T09:28:02.503Z
tags: medical, medical guide, work in progress
editor: markdown
dateCreated: 2024-08-12T07:53:01.066Z
---

This is where you'll start learning about the current medical system used on Equinox. The code uses a modified Erismed4 with various new medicines and systems to tackle.
> The content of this page is subjected to change as development is currently in the work.
{.is-warning}

# The Basics
It is first and foremost importnat to note that anyone can be stabilized no matter their condition, this is ultimately up to the equipment at hand and the knowledge that you have. Do not beat yourself up over mistakes trying to learn the game!


## Damage Types
There are 4 primary damage types within the game, each can be caused by different afflictions, or as a consequence of less physical means.
* As a general note, the body will naturally heal from these damage, although usually at a very slow pace. More than occasionally, the focus would be to stabilize the patient and stop what is causing the damage.


### Brute
<span style="color: red;">Brute damage</span> are bruising, cuts, lacerations, and pierced wounds. They make up the <span style="color: red;">red</span> number in the medical scanner and can be examined by looking. 

* Brutes are caused by being directly damaged by hostile enemies, stabbed, slashed, or shot at.
* A high enough brute damage may break bones, damage internal organs, or even dismember limbs.
* [Bleeding](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#bloodloss) is usually accompanied alongside brute damage, which causes bloodloss.

These are common ways to treat brute damage;
* Using a gauze or brute treatment kit on the affected limb. This also stops bleeding.
* [Tricordizine](), [Bicardine](), and [Meralyn]() can be used to heal brute damage overtime.


### Burn
<span style="color: orange;">Burn damage</span> are burns and peeling skin or scarring wounds. They make up the <span style="color: orange;">orange</span> number in the medical scanner and can be examined by looking.

* Burns are caused by fire, heat, acid burns, or in some case even [radiation](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#radiation).
* Burns may cause damage to internal organs, [infection, or even necrosis](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#infection).

These are common ways to treat burn damage;
* Using an ointment or burn treatment kit on the affected limb.
* [Tricordizine](), [Kelotane](), and [Dermaline]() can be used to heal burn damage overtime.


### Toxin
<span style="color: lime;">Toxin damage</span> are toxin threshold or the toxicity level of one's blood caused by poisoning. This refers to the <span style="color: lime;">green</span> number in the medical scanner. Toxin are processed overtime, and may worsen or get better depending on whether the patient still has poison in their blood.

Toxins can be caused by different reasons such as;
* Poison caused by being bitten or injected by spiders or other types of fauna.
* Using harmful chemicals, drugs, or overdosing.
* Touching toxic or biohazard substances.
* Breathing in harmful gases such as roach gas or plasma gas.

These are common ways to treat toxin damage;
* The most important aspect is to remove poison, toxic, or harmful substance from the patient's body using [dialysis]() methods, [purging chemicals](), or [stomach pump]()
* [Tricordizine]() or [Arithrazine](), additionally, [Dylovene]() and [Carthatoline]() also purge toxin from the patient's blood.


### Oxyloss
<span style="color: cyan;">Oxyloss</span>, or suffocation, refers to the <span style="color: cyan;">blue</span> number in the medical scanner. This is hypoxia or lack of oxygen to the brain. It is crucial to the patient, as they are truly dead when their brain dies from direct damage or lack of oxygen. 

Oxyloss can be caused by different reasons such as;
* Lack of breathable air in the environment or internal tank.
* Specific poison, toxins, or other chemical effects.
* [Bloodloss aka bleeding](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#bloodloss), or lack of blood which disallow oxygen to be transferred to the brain.
* Dead, damaged, or missing lungs, or a lack of heart disallowing blood to be pumped to the brain.

There are a few ways to mediate or treat oxyloss;
* [Inapprovaline]() included in the emergency autoinjector, although this only stop it from going worse.
* [Tricordrazine](), [Dexalin]() and [Dexalin plus](), which treats oxyloss damage, but does not stop what is causing the damage.
* [Stopping bleeding](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#bloodloss) and provide [blood transfusion](), repair lungs and relevant organs, removing the toxin in the patient, or making sure the environment is breathable again.


## Other Types of Injury

### Bloodloss

Bloodloss refers the patient's lack of blood caused by bleeding. This is usually displayed in percentage level on the medical scanner from 0% to 100% with a `u` (unit) number marking how many units of blood volume is in a person. 

Below **70%**, the person starts to suffer from <span style="color: cyan;">oxyloss</span>, as such, it is very important to focus on stopping the bleed first.

* Bleeding can be stopped by using gauze, brute treatment kit, or any medicine with blood-clotting property such as [Quickclot]() or [Bicardine]().
* Bleeding can also be manually stopped by hand. Target the person's limb that is bleeding, `reinforced grab` + `help intent click` on the person.

Blood can be regained naturally over time with rest and food, but in severe case of blood loss, use [transfusion]() of saline or the appropriate bloodtype.


### Fractures

Fractures refer to cracks or breakage of the bone in a person's limb or body. This is usually caused by excessive brute damage. Fractures are painful and, in breakage case, if left unattended will damage internal organs. 

To learn the specifics of the location of the fracture, a [body scanner machine]() is required, or using [body inspection method](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#triage-and-transport)

* Fractures can be mediated from getting worse or damaging internal organs with the use of a splint.
* Fractures are treated by the means of [surgery]() or medicine with bone-mending property such as [Ossisine]().


### Infection

Infection refers to the level of which a limb is infected by bacteria. This is usually the result of a bad, untreated burns or internal burns. The infection progress from internal burns through stages, eventually killing affected internal organs, causing them to be [necrotic]()

* Infection itself is treated by [Spaceacillin]().
* Internal burns and necrosis are treated by [surgery]() or [Trypsin]().


### Radiation
Radiation refers to the level of radiation a person has been afflicted with. This is usually counted in percentage level in the medical scanner which starts from 0% and can go beyond 100%. A radiation level abot 50% is unsafe, and gets progressively more severe. 

The patient will exhibit burning of their skin across their body, hairloss, and even [genetics damage](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#genetics) which causes tumor growth in higher radiation levels alongside high level of pain. Radiation can occur in a few ways;
* Being within the proximity of radioactive substances, such as the [Supermatter](), [Kaiser roach]()'s radioactive spit, [Ameridians](), radioactive waste, and even other highly irradiated matters.
* Being hit or damaged by radioactive projectiles caused by weapons or hostile entities.

Radiation level is directly treated  by injecting the patient [Hyronalin]() or [Arithrazine]() and regularly monitor.
* Radiation level is also mitigated by using radiation proof suits marked with percentage number of how much radiation is mitigated, e.g. 75/25 means 75% and 100/25 means 100%.

### Genetics Damage

Also referred to as "cloneloss", which can be caused by genetics instability caused by some organisms or genetics project failure. Newly cloned subjects will also come out of their vat with this. Genetics damage shows up on the medical scanner, but a [body scanner]() is needed to learn the specifics.

Genetics damage reduces your overall health, a patient with 30 genetics damage and 100 base health will have a max health of 70. Additionally, genetics damage causes tumor growth which, if left untreated can become severely lethal.

* Tumors are divided into two types, each slowly progressing from a plasm stage till it is fully grown.
  * Benign tumor once fully grown will cause the limb to be less effective, but does not spread or cause serious damage.
  * Malignant tumor is the more serious version of this, it will slowly kill the organ off before spreading to other organs.
* [Rezadone]() and [Ryetalyn]() treats genetics damage, and additionally removes both types of tumor.
* [Cryoxadone]() and [Cronexidone]() when used alongside the [cryotube]() will also treat genetics damage. The former only remove benign tumor, the latter will remove both types of tumor.
* [Peridaxon]() additionally removes benign tumor, but does not treat genetics damage on its own.


### Organ Damage

Organ damage refers to any types of damage applied to the organ directly. In some cases this is a flat damage, in other cases it may be a [wound type]() that requires specific medicine or [surgery steps]().
* In general, all organs (excluding the bone) can be healed with [Peridaxon]()
* Specific organs can be healed using special medicine, such as [Imidazoline]() repairing the eyes, or [Respirodaxon]() for the lungs. Specifics of which you can find [here]().
* Once an organ is dead, it is considered damaged beyond repair and will not function and needs to be replaced via [surgery]()



## Triage and Transport


