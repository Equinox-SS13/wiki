---
title: Guide to Medicine
description: All you need to start out as a doctor or field medic.
published: false
date: 2024-08-14T10:40:47.510Z
tags: medical, guide, medical guide, work in progress
editor: markdown
dateCreated: 2024-08-12T07:53:01.066Z
---

This is where you'll start learning about the current medical system used on Equinox. The code uses a modified Erismed4 with various new medicines and systems to tackle.
> The content of this page is subjected to change as development is currently in the work.
{.is-warning}

# Basic Damage Types
It is first and foremost importnat to note that anyone can be stabilized no matter their condition, this is ultimately up to the equipment at hand and the knowledge that you have. Do not beat yourself up over mistakes trying to learn the game!

There are 4 primary damage types within the game, each can be caused by different afflictions, or as a consequence of less physical means.
* As a general note, the body will naturally heal from these damage, although usually at a very slow pace. More than occasionally, the focus would be to stabilize the patient and stop what is causing the damage.


### Brute
<span style="color: red;">Brute damage</span> are bruising, cuts, lacerations, and pierced wounds. They make up the <span style="color: red;">red</span> number in the medical scanner and can be examined by looking. 

* Brutes are caused by being directly damaged by hostile enemies, stabbed, slashed, or shot at.
* A high enough brute damage may break bones, damage internal organs, or even dismember limbs.
* [Bleeding](/guides/medical-guides/Guide-to-Medicine#bloodloss) is usually accompanied alongside brute damage, which causes bloodloss.
* If left untreated, bruises and cuts can lead to [infection](/guides/medical-guides/Guide-to-Medicine#infection).

These are common ways to treat brute damage;
* Using a gauze or brute treatment kit on the affected limb. This also stops bleeding.
* [Tricordizine](), [Bicardine](), and [Meralyn]() can be used to heal brute damage overtime.


### Burn
<span style="color: orange;">Burn damage</span> are burns and peeling skin or scarring wounds. They make up the <span style="color: orange;">orange</span> number in the medical scanner and can be examined by looking.

* Burns are caused by fire, heat, acid burns, or in some case even [radiation](/guides/medical-guides/Guide-to-Medicine).
* Burns may cause damage to [internal organs](/guides/medical-guides/Guide-to-Medicine#internal-burns] and lead to [infection](/guides/medical-guides/Guide-to-Medicine#infection), or even [necrosis](/guides/medical-guides/Guide-to-Medicine#necrosis).

These are common ways to treat burn damage;
* Using an ointment or burn treatment kit on the affected limb.
* [Tricordizine](), [Kelotane](), and [Dermaline]() can be used to heal burn damage overtime.


### Toxin
<span style="color: lime;">Toxin damage</span> are toxin threshold or the toxicity level of one's blood caused by poisoning. This refers to the <span style="color: lime;">green</span> number in the medical scanner. Toxin are processed overtime, and may worsen or get better depending on whether the patient still has poison in their blood.

The patient will also vomit if high levels of toxin is within their blood or stomach, this is the body's response to poison and is a good determination that someone has toxin damage.

Toxins can be caused bydifferent reasons such as;
* Poison caused by being bitten or injected by spiders or other types of fauna.
* Using harmful chemicals, drugs, or overdosing.
* Touching toxic or biohazard substances.
* Breathing in harmful gases such as roach gas or plasma gas.
* Toxins, poisons, and overdose also comes with an affect on one's [Neural System Accumulation](/guides/medical-guides/Guide-to-Medicine#neural-system-accumulation).


These are common ways to treat toxin damage;
* The most important aspect is to remove poison, toxic, or harmful substance from the patient's body using [dialysis]() methods, [purging chemicals](), or [stomach pump]()
* [Tricordizine]() or [Arithrazine](), additionally, [Dylovene]() and [Carthatoline]() also purge toxin from the patient's blood.


### Oxyloss
<span style="color: cyan;">Oxyloss</span>, or suffocation, refers to the <span style="color: cyan;">blue</span> number in the medical scanner. This is hypoxia or lack of oxygen to the brain. It is crucial to the patient, as they are truly dead when their brain dies from direct damage or lack of oxygen. 

The lack of oxygen also ususally paired with [blood loss](/guides/medical-guides/Guide-to-Medicine#bloodloss) which in severe cases will start killing organs if left for too long.

Oxyloss can be caused by different reasons such as;
* Lack of breathable air in the environment or internal tank.
* Specific poison, toxins, or other chemical effects.
* [Bloodloss aka bleeding](/guides/medical-guides/Guide-to-Medicine#bloodloss), or lack of blood which disallow oxygen to be transferred to the brain.
* Dead, damaged, or missing lungs, or a lack of heart disallowing blood to be pumped to the brain.

There are a few ways to mediate or treat oxyloss;
* [Inapprovaline]() included in the emergency autoinjector, although this only stop it from going worse.
* [Tricordrazine](), [Dexalin]() and [Dexalin plus](), which treats oxyloss damage, but does not stop what is causing the damage.
* [Stopping bleeding](/guides/medical-guides/Guide-to-Medicine#bloodloss) and provide [blood transfusion](), repair lungs and relevant organs, removing the toxin in the patient, or making sure the environment is breathable again.


# Other Types of Injury

## Bloodloss

Bloodloss refers the patient's lack of blood caused by bleeding. This is usually displayed in percentage level on the medical scanner from 0% to 100% with a `u` (unit) number marking how many units of blood volume is in a person. 

Below **70%**, the person starts to suffer from <span style="color: cyan;">oxyloss</span>, as such, it is very important to focus on stopping the bleed first. Lack of blood can cause oxyloss, and even organ damage and death from the lack of bloodflow.

* Bleeding can be stopped by using gauze, brute treatment kit, or any medicine with blood-clotting property such as [Quickclot]() or [Bicardine]().
* Bleeding can also be manually stopped by hand. Target the person's limb that is bleeding, `reinforced GRAB` + `HELP intent click` on the person.

Blood can be regained naturally over time with rest and food, but in severe case of blood loss, use [transfusion]() of saline or the appropriate bloodtype.


## Fractures

Fractures refer to cracks or breakage of the bone in a person's limb or body. This is usually caused by excessive brute damage. Fractures are painful and, in breakage case, if left unattended will damage internal organs. Extreme breakage may be spotted by examining the patient.

To learn the specifics of the location of the fracture, a [body scanner machine](/guides/medical-guides/Guide-to-Medicine#body-scanner) is required, or using [body inspection method](/guides/medical-guides/Guide-to-Medicine#inspecting-limb)

* Any form of fractures can be mediated from getting worse or damaging internal organs with the use of a [splint](/guides/medical-guides/Guide-to-Medicine#splint).
* Fractures are treated by the means of [surgery]() or medicine with bone-mending property such as [Ossisine]().
* To see the specifics of damage types to the bone and how to treat them, see [bone damage](https://wiki.bluespace.engineer/e/en/guides/medical-guides/Guide-to-Medicine#bone-damage)

### Dislocation
Not an actual fracture, but sometimes the patient's limb may be dislocated, causing a lot of pain and incapacitating the limb.
* To fix this, a person will have to perform a `UNDISLOCATE-JOINT` verb on the patient by `right-clicking` and choosing the option in the dropdown menu. This causes a lot of pain.


## Radiation

Radiation refers to the level of radiation a person has been afflicted with. This is usually counted in percentage level in the medical scanner which starts from 0% and can go beyond 100%. A radiation level abot 50% is unsafe, and gets progressively more severe. 

The patient will exhibit burning of their skin across their body, hairloss, and even [genetics damage](/guides/medical-guides/Guide-to-Medicine#genetics) which causes tumor growth in higher radiation levels alongside high level of pain. Radiation can occur in a few ways;
* Being within the proximity of radioactive substances, such as the [Supermatter](), [Kaiser roach]()'s radioactive spit, [Ameridians](), radioactive waste, and even other highly irradiated matters.
* Being hit or damaged by radioactive projectiles caused by weapons or hostile entities.

Radiation level is directly treated  by injecting the patient [Hyronalin]() or [Arithrazine]() and regularly monitor.
* Radiation level is also mitigated by using radiation proof suits marked with percentage number of how much radiation is mitigated, e.g. 75/25 means 75% and 100/25 means 100%.


## Genetics Damage

Also referred to as "cloneloss", which can be caused by genetics instability caused by some organisms or genetics project failure. Newly cloned subjects will also come out of their vat with this. Genetics damage shows up on the medical scanner, but a [body scanner](/guides/medical-guides/Guide-to-Medicine#body-scanner) is needed to learn the specifics.

Genetics damage reduces your overall health, a patient with 30 genetics damage and 100 base health will have a max health of 70. Additionally, genetics damage causes tumor growth which, if left untreated can become severely lethal.

* Tumors are divided into two types, each slowly progressing from a plasm stage till it is fully grown.
  * Benign tumor once fully grown will cause the limb to be less effective, but does not spread or cause serious damage.
  * Malignant tumor is the more serious version of this, it will slowly kill the organ off before spreading to other organs.
* [Rezadone]() and [Ryetalyn]() treats genetics damage, and additionally removes both types of tumor.
* [Cryoxadone]() and [Cronexidone]() when used alongside the [cryotube]() will also treat genetics damage. The former only remove benign tumor, the latter will remove both types of tumor.
* [Peridaxon]() additionally removes benign tumor, but does not treat genetics damage on its own.


## Organ Damage

Organ damage refers to any types of damage applied to the organ directly. In some cases this is a flat damage, in other cases it may be a [wound type](/guides/medical-guides/Guide-to-Medicine#internal-wounds) that requires very specific medicine or [surgery steps]().
* In general, all organs (excluding the bone) can be healed with [Peridaxon]()
* Specific organs can be healed using special medicine, such as [Imidazoline]() repairing the eyes, or [Respirodaxon]() for the lungs. Specifics of which you can find [here]().
* Once an organ is dead, it is considered damaged beyond repair and will not function and needs to be replaced via [surgery](). This is also very painful.

The following are a list of organ and what happens when they are dead, or destroy.
|----------|------------------------------|----------|----------------------------------------|
| Brain    | Death of the person and their consciousness | Heart    | Death of other organs by lack of bloodflow. |
| Lungs    | Inability to breath oxygen, causing death of other organs | Liver    | Inability to process chemicals and allowing toxin to build up. |
| Kidneys  |                              | Stomach  | Inability to digest food or take nutrients by mouth |
| Appendix  | Nothing, the appendix is functionless | Bone     | Loss of the limb or body part |
| Blood vessel | Lack of bloodflow to the limb or body part | Nerve | Loss of [NSA](/guides/medical-guides/Guide-to-Medicine#neural-system-accumulation) and function of the limb or body part |
| Muscle   | Loss of function of the limb or body part. | | |

* It has to be noted that, out of all organs, bones are unaffected by the lack of bloodflow and oxygen.

## Pain

Although not an actual, physical damage by itself, pain will make injuries much more difficult to manage. A patient who is in pain will be unable to focus on task at hand as well, be slowed down, collapses, drop whatever may be on their hand, and even black out unconscious at time.
* Pain can be managed by using painkillers and other opioids, be careful of [NSA](/guides/medical-guides/Guide-to-Medicine#neural-system-accumulation).
* To mediate the pain for surgery, the patient can be put to sleep by means of [anesthesia](/guides/medical-guides/Guide-to-Surgery#preparing-the-patient) or [Soporific]().

---

# Triage and Transport

Now that you know about types of damage and a general idea of how to treat them, we have to talk about Triaging.

Triage refers to the concept of preliminary assessment of the urgency of a patient's need for treatment. In short, quickly identifying the type of injury, who to prioritize first, and steps to act to stabilize them.

## Patient's Health and Diagnosis

The most important and often overlooked step in determining if a person is injured and how injured is by looking. You can examine a person by `shift` + `left clicking` and reading the examine text underneath.

This step alone allow us to see the severity of the situation, a few things to first note;
* Is the patient conscious or not? Are they constantly blacking out?
* Are they breathing, bleeding, screaming, gasping for air, or seem to be alive?
* What is the severity of their visible wound? If the wound is not visible, is a scan needed?

If you have been provided a medical HUD interface, a visible graphical visualization of a person's health will be visible above them. The following are stages of their health;
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth100.gif width="64" height="10" class="sub health-indicator">: 100% healthy</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth80.gif width="64" height="10" class="sub health-indicator">: less than 100% health</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth60.gif width="64" height="10" class="sub health-indicator">: less than 70% health</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth40.gif width="64" height="10" class="sub health-indicator">: less than 50% health</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth25.gif width="64" height="10" class="sub health-indicator">: less than 30% health</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth10.gif width="64" height="10" class="sub health-indicator">: less than 18% health</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth1.gif width="64" height="10" class="sub health-indicator">: less than 5% health</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth0.gif width="64" height="10" class="sub health-indicator">: less than 0%, this is also known as "in critical stage"</div>
* <div style="display: flex; align-items: center;"><img src=/game_sprites/medhudstates/hudhealth-100.gif width="64" height="10" class="sub health-indicator">: the patient is dead</div>

### Diagnosis

In general, examining a person by looking will tell you a lot about their condition. Occasionally however, further steps are needed to diagnose the patient outside of what you see and hear.

#### Health Scanner
A handheld [health analyzer](/guides/medical-guides/Guide-to-Medicine#health-analyzer) can be used to give a lot of information on the patient, this includes things one cannot see or hear such as blood level, toxin level, what and how much chemical is in the patient's blood, radiation damage, and even genetics damage.

#### Full-body Scan
A [body scanner](/guides/medical-guides/Guide-to-Medicine#body-scanner) can give the most detailed explanation of the patients state compared to a health analyzer down to each individual bones and organs. This is extremely useful as a medical personnel to be able to determine the next cause of treatment.

#### Inspecting Limb
A manual inspection of the patients limb by `passive GRAB` + `HELP intent click` on the targeted limb. This is timely but allows the inspector to tell if the limb has any damage, broken bones, or wounds.


## Transporting the Patient

More time than not, a person will be injured away from the medical facility and personnel, which makes transporting the patient to the treatment facility a very crucial part. Often you'll be fighting against time moving a patient over distance, time that they may not have.

A correct step of transportation should also be considered to not cause further harm to the patient and cause unintentional death.

### Stabilizing a Patient

A quick examine or diagnosis should be performed by now to determine if they need to be transported. If they are to be transported, here are a few steps to stabilize a patient quickly so that they can be moved safely.
* Stop all bleeding using a gauze, brute treatment kit, or Quickclot.
* If a patient is gasping for air, everyone has an emergency injector within their supply box, use it.
* Splint the affected limb where [sharpnel](/guides/medical-guides/Guide-to-Surgery) or bone fracture is located.
* If a [stasis bag](h/guides/medical-guides/Guide-to-Medicine#stasis-bag) is available, it might be a good idea to use them on a critically injured patient to stop them from getting worse.
* An initial treatment using available medical supply may be wise, as it extends the time you have to transport the person.

### Movement Methods

In the case that a person is able to walk still and conscious, using the `PULL` action on them is safe and allow for quick and mobile movement.

However, this gets complicated when a person becomes dead, incapacitated, or unconscious. By performing a `PULL` option on the injured at this stage, dragging them along the floor will make wounds worse and cause constant brute damage to them.
* Using a roller bed or a movable office chair will allow for safe and quick transport of the patient.
* Putting them in a bag (such as body bag or [stasis bag](/guides/medical-guides/Guide-to-Medicine#stasis-bag)) will also work.
* Using a `GRAB intent` option will cause you to slow down a bit, but this is considered safe if no option is available.


## Reviving the Dead

Rarely, you'll find yourself with a dead patient. When a patient dies, all their bodily function cease and they begin to slowly decay overtime; blood stops flowing and the organ starts to slowly die. Simply put; the body will begin to rot and get worse the longer they are dead.

This makes the difference between newly deceased person and one that deceased for a long or unknown amount of time very different. As always, execute precautions when transporting the patient and call out for assistance if needed.

### Resustication

Despite death, resustication is always possible. A timer is started on death which determines when their brain decay and when resustication is not possible without surgical intervention.
* Past 15 minutes, the brain starts to decay and take damage.
* Past 30 minutes, resustication is not possible with out [surgical intervention](https://wiki.bluespace.engineer/e/en/guides/medical-guides/Guide-to-Surgery#resustication-preparation).

### Stasis

There is, however, a way to completely halt the degradation of patient's health and practically stabilizing them by stopping all their bodily function. 

This is called stasis, and it works to stop a patient in critical stages from death as well as stopping body from rotting past resustication timer. There are two way to put someone in a stasis.
* [Cryogenics tube](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#cryogenics-tube) when set up correctly and paired with [Cryoxadone]() or [Cronexidone]() can be used to put someone in an indefinite stasis state.
* Disposable [stasis bag](https://wiki.bluespace.engineer/en/guides/medical-guides/Guide-to-Medicine#stasis-bag) can be used to store someone inside, this effects slowly wane off eventually, and should be used for transport.

# Administering Medicine

## Oral, Injection, and Touch

## Neural System Accumulation

## Intravenous Therapy (IV)


---

# Internal Wounds

Wound types are not the damage themselves, but the result of the damage applied to the person. For example, getting hit with a club causes blunt wound, while getting stabbed with a knife causes laceration. 

These are wounds that only apply to internal organs where they are hit (such as muscles, liver, or nerves) and may be treated with either [surgery](/guides/medical-guides/Guide-to-Surgery) or [medicine]().

Internal wounds have stages of progress, which takes the place of a number like `0/10` whereas 0 is the first stage, and 10 is the last stage.

## Blunt, Sharp, and Swelling

### Blunt and Sharp Wounds

<span style="color: red;">Blunt and sharp wounds</span> are caused by brute damage with a difference in it's severity. This is divided into 3 different levels depending on how the damage was applied.

* Blunt wounds occur as a result of bruises caused by blunt objects and non-penetrating rounds. They appear in the form of rupture, internal hemorrhage, or contusion.
  * Blunt wound can be healed using [brute treatment kit surgery](/guides/medical-guides/Guide-to-Surgery#internal-organ-repair), or medicine with brute healing or blood clotting property.
* Sharp wounds are caused by bladed weapons or penetrating rounds. They appear in the form of perforation, cavitation, gored tissue, laceration, deep gash, or ripped tissue.
  * If left untreated, a sharp wound will start to [swell](/guides/medical-guides/Guide-to-Medicine#swelling) before turning into an [infection](/guides/medical-guides/Guide-to-Medicine#infection).
  * Sharp wounds require either [brute treatment kit surgery](/guides/medical-guides/Guide-to-Surgery#internal-organ-repair) or medicine with a stronger brute healing or blood clotting property.

### Swelling

<span style="color: salmon;">Swelling</span> is the consequence of leaving an open internal wound untreated, causing bacteria to form. The area will be painful to touch, and leaving it untreated will cause an infection.
* Swelling takes the form of swelling or abcess of the organ or body part.
* Swelling can be treated before it becomes infected using antibiotics such as [Spaceacillin]()

## Burns and Necrosis

### Internal Burns

<span style="color: orange;">Burn wounds</span> are caused by excessive burn damage. This will cause internal burns on the organ or limb, progressing into an [infection](/guides/medical-guides/Guide-to-Medicine#infection) if left untreated.
* Internal burns take the form of scorched tissue, charred tissued, or incinerated flesh.
* Internal burns can be stabilized using [Inapprovaline](), but this does not treat it.
* Internal burns can be treated before it becomes infected using [burn treatment kit surgery](/guides/medical-guides/Guide-to-Surgery#internal-organ-repair), [cutting out the damaged tissue](/guides/medical-guides/Guide-to-Surgery#damaged-tissue-and-necrosis-removal), or [Trypsin]().

Once treated, internal burns will left a scarring of [necrosed tissues](/guides/medical-guides/Guide-to-Medicine#necrosis), which will need to be treated further.

### Necrosis

<span style="color: grey;">Necrosis</span> are divided into two types; damaged tissues which slowly progress into necrosis. Both of which causes pain for the patient and if left untreated, will progress into an [infection](/guides/medical-guides/Guide-to-Medicine#infection).
* Necrosis takes the form of damaged tissue and necrotizing tissue for the respective levels.
* Like internal burns, necrosis can be stabilized using [Inapprovaline](), but this does not treat it.
* Like internal burns, necrosis can be treated using [necrosis removal surgery](/guides/medical-guides/Guide-to-Surgery#damaged-tissue-and-necrosis-removal) or [Trypsin]().

## Infection

<span style="color: gold;">Infection</span> is caused by accumulation of bacteria, on untreated wounds. Once this happens, the infection will slowly damage organs, spread to other organs, and start killing them until the organs and the patient are dead. Generally, infection can be spotted by examining the patient from the outside.
* Infection can be treated using antibiotic [Spaceacillin]().
* If left untreated, infection will spread and damage organs until they are dead.

## Poison and Heavy Poison

<span style="color: lime;">Poison and heavy poison</span> are caused by overdosing and inhalation or injection of extremely harmful substances. Both types are painful, and are divided into multiple category as follows;

Poisoning can be cured by [cutting out the affected tissue](/guides/medical-guides/Guide-to-Surgery#damaged-tissue-and-necrosis-removal), [brute treatment kit surgery](/guides/medical-guides/Guide-to-Surgery#internal-organ-repair), or using antitoxin such as [Dylovene]() or stronger.
* Pustule makes the organ slightly bigger, filling up the space within the limb.
* Minor poisoning makes the organ much less efficient, requiring

## Foreign Objects

## Tumors

## Bone Wounds

---

# Medical Equipment

## Necessary Equipment

#### Health Analyzer

#### Syringe

#### Medical HUD

#### Roller Bed and Advanced Roller Bed

#### Defibrilator

#### Stasis Bag

#### Hypospray

## Machinery

#### Body Scanner

#### Sleeper

#### Cryogenics Tube

## Other Equipment

#### Latex and Nitrile gloves

#### Stethoscope

#### Labcoat

#### Portable Freezer

### Surgical Equipment

### Chemistry Equipment