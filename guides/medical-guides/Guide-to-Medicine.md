---
title: Guide to Medicine
description: All you need to start out as a doctor or field medic.
published: true
date: 2024-09-03T14:30:00.854Z
tags: 
editor: markdown
dateCreated: 2024-08-12T07:53:01.066Z
---

> [**Work in Progress**](/maintenance/Templates#work-in-progress): This article is **incomplete** and is being **actively worked on** by user: `@emilitiaennehrt`
{.is-warning}

This is where you'll start learning about the current medical system used on Equinox. The code uses a modified Erismed4 with various new medicines and systems to tackle.


# Basic Damage Types
It is first and foremost importnat to note that anyone can be stabilized no matter their condition, this is ultimately up to the equipment at hand and the knowledge that you have. Do not beat yourself up over mistakes trying to learn the game!

There are 4 primary damage types within the game, each can be caused by different afflictions, or as a consequence of less physical means.
* As a general note, the body will naturally heal from these damage, although usually at a very slow pace. More than occasionally, the focus would be to stabilize the patient and stop what is causing the damage.


### Brute
<span style="color: red;">Brute damage</span> are bruising, cuts, lacerations, and pierced wounds. They make up the <span style="color: red;">red</span> number in the medical scanner and can be examined by looking. 

* Brutes are caused by being directly damaged by hostile enemies, stabbed, slashed, or shot at.
* A high enough brute damage may break bones, damage internal organs, or even dismember limbs.
* [Bleeding](#bloodloss) is usually accompanied alongside brute damage, which causes bloodloss.
* If left untreated, bruises and cuts can lead to [infection](#infection).

These are common ways to treat brute damage;
* Using a gauze or brute treatment kit on the affected limb. This also stops bleeding.
* [Tricordizine](), [Bicardine](), and [Meralyn]() can be used to heal brute damage overtime.


### Burn
<span style="color: orange;">Burn damage</span> are burns and peeling skin or scarring wounds. They make up the <span style="color: orange;">orange</span> number in the medical scanner and can be examined by looking.

* Burns are caused by fire, heat, acid burns, or in some case even [radiation](#radiation).
* Burns may cause damage to [internal organs](#internal-burns) and lead to [infection](#infection), or even [necrosis](#necrosis).

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
* Toxins, poisons, and overdose also comes with an affect on one's [Neural System Accumulation](#neural-system-accumulation).


These are common ways to treat toxin damage;
* The most important aspect is to remove poison, toxic, or harmful substance from the patient's body using [dialysis]() methods, [purging chemicals](), or [stomach pump]()
* [Tricordizine]() or [Arithrazine](), additionally, [Dylovene]() and [Carthatoline]() also purge toxin from the patient's blood.


### Oxyloss
<span style="color: cyan;">Oxyloss</span>, or suffocation, refers to the <span style="color: cyan;">blue</span> number in the medical scanner. This is hypoxia or lack of oxygen to the brain. It is crucial to the patient, as they are truly dead when their brain dies from direct damage or lack of oxygen. 

The lack of oxygen also ususally paired with [blood loss](#bloodloss) which in severe cases will start killing organs if left for too long.

Oxyloss can be caused by different reasons such as;
* Lack of breathable air in the environment or internal tank.
* Specific poison, toxins, or other chemical effects.
* [Bloodloss aka bleeding](#bloodloss), or lack of blood which disallow oxygen to be transferred to the brain.
* Dead, damaged, or missing lungs, or a lack of heart disallowing blood to be pumped to the brain.

There are a few ways to mediate or treat oxyloss;
* [Inapprovaline]() included in the emergency autoinjector, although this only stop it from going worse.
* [Tricordrazine](), [Dexalin]() and [Dexalin plus](), which treats oxyloss damage, but does not stop what is causing the damage.
* [Stopping bleeding](#bloodloss) and provide [blood transfusion](), repair lungs and relevant organs, removing the toxin in the patient, or making sure the environment is breathable again.


# Other Types of Injury

## Bloodloss

Bloodloss refers the patient's lack of blood caused by bleeding. This is usually displayed in percentage level on the medical scanner from 0% to 100% with a `u` (unit) number marking how many units of blood volume is in a person. 

Below **70%**, the person starts to suffer from <span style="color: cyan;">oxyloss</span>, as such, it is very important to focus on stopping the bleed first. Lack of blood can cause oxyloss, and even organ damage and death from the lack of bloodflow.

* Bleeding can be stopped by using gauze, brute treatment kit, or any medicine with blood-clotting property such as [Quickclot]() or [Bicardine]().
* Bleeding can also be manually stopped by hand. Target the person's limb that is bleeding, `reinforced GRAB` + `HELP intent click` on the person.

Blood can be regained naturally over time with rest and food, but in severe case of blood loss, use [transfusion](#intravenous-therapy-iv) of saline or the appropriate bloodtype.

### Blood Type

Different people will have different blood type ranging from -O to +AB. Some blood types are compatible with other, but those that do not cannot be transfused into the patient otherwise risking blood toxicity.

`This should be read left to right, as in blood type to patient`

| Can be transferred to... |-O|+O|-A|+A|-B|+B|-AB|+AB|
| -  | - | - | - | - | - | - | - | - |
| <center>-O</center> | Y | Y | Y | Y | Y | Y | Y | Y |
| <center>+O</center> | * | Y | * | Y | * | Y | * | Y |
| <center>-A</center> | * | * | Y | Y | * | * | Y | Y |
| <center>+A</center> | * | * | * | Y | * | * | * | Y |
| <center>-B</center> | * | * | * | * | Y | Y | Y | Y |
| <center>+B</center> | * | * | * | * | * | Y | * | Y |
| <center>-AB</center> | * | * | * | * | * | * | Y | Y |
| <center>+AB</center> | * | * | * | * | * | * | * | Y |



## Fractures

Fractures refer to cracks or breakage of the bone in a person's limb or body. This is usually caused by excessive brute damage. Fractures are painful and, in breakage case, if left unattended will damage internal organs. Extreme breakage may be spotted by examining the patient.

To learn the specifics of the location of the fracture, a [body scanner machine](#body-scanner) is required, or using [body inspection method](#inspecting-limb)

* Any form of fractures can be mediated from getting worse or damaging internal organs with the use of a [splint](#splint).
* Fractures are treated by the means of [surgery]() or medicine with bone-mending property such as [Ossisine]().
* To see the specifics of damage types to the bone and how to treat them, see [bone damage](https://wiki.bluespace.engineer/e/en#bone-damage)

### Dislocation
Not an actual fracture, but sometimes the patient's limb may be dislocated, causing a lot of pain and incapacitating the limb.
* To fix this, a person will have to perform a `UNDISLOCATE-JOINT` verb on the patient by `right-clicking` and choosing the option in the dropdown menu. This causes a lot of pain.


## Radiation

Radiation refers to the level of radiation a person has been afflicted with. This is usually counted in percentage level in the medical scanner which starts from 0% and can go beyond 100%. A radiation level abot 50% is unsafe, and gets progressively more severe. 

The patient will exhibit burning of their skin across their body, hairloss, and even [genetics damage](#genetics) which causes tumor growth in higher radiation levels alongside high level of pain. Radiation can occur in a few ways;
* Being within the proximity of radioactive substances, such as the [Supermatter](), [Kaiser roach]()'s radioactive spit, [Ameridians](), radioactive waste, and even other highly irradiated matters.
* Being hit or damaged by radioactive projectiles caused by weapons or hostile entities.

Radiation level is directly treated  by injecting the patient [Hyronalin]() or [Arithrazine]() and regularly monitor.
* Radiation level is also mitigated by using radiation proof suits marked with percentage number of how much radiation is mitigated, e.g. 75/25 means 75% and 100/25 means 100%.


## Genetics Damage

Also referred to as "cloneloss", which can be caused by genetics instability caused by some organisms or genetics project failure. Newly cloned subjects will also come out of their vat with this. Genetics damage shows up on the medical scanner, but a [body scanner](#body-scanner) is needed to learn the specifics.

Genetics damage reduces your overall health, a patient with 30 genetics damage and 100 base health will have a max health of 70. Additionally, genetics damage causes [tumor growth](#Tumors) which, if left untreated can become severely lethal.

* [Tumors](#Tumors) are divided into two types, each slowly progressing from a plasm stage till it is fully grown.
  * Benign tumor once fully grown will cause the limb to be less effective, but does not spread or cause serious damage.
  * Malignant tumor is the more serious version of this, it will slowly kill the organ off before spreading to other organs.
* [Rezadone]() and [Ryetalyn]() treats genetics damage, and additionally removes both types of tumor.
* [Cryoxadone]() and [Cronexidone]() when used alongside the [cryotube]() will also treat genetics damage. The former only remove benign tumor, the latter will remove both types of tumor.
* [Peridaxon]() additionally removes benign tumor, but does not treat genetics damage on its own.


## Organ Damage

Organ damage refers to any types of damage applied to the organ directly. In some cases this is a flat damage, in other cases it may be a [wound type](#internal-wounds) that requires very specific medicine or [surgery steps]().
* In general, all organs (excluding the bone) can be healed with [Peridaxon]()
* Specific organs can be healed using special medicine, such as [Imidazoline]() repairing the eyes, or [Respirodaxon]() for the lungs. Specifics of which you can find [here]().
* Once an organ is dead, it is considered damaged beyond repair and will not function and needs to be replaced via [surgery](). This is also very painful.

The following are a list of organ and what happens when they are dead, or destroy.

|||||
|----------|------------------------------|----------|----------------------------------------|
| Brain    | Death of the person and their consciousness | Heart    | Death of other organs by lack of bloodflow. |
| Lungs    | Inability to breath oxygen, causing death of other organs | Liver    | Inability to process chemicals and allowing toxin to build up |
| Kidneys  | Inability to regenerate blood and allowing toxin to build up | Stomach  | Inability to digest food or take nutrients by mouth |
| Appendix  | Nothing, the appendix is functionless | Bone     | Loss of the limb or body part |
| Blood vessel | Lack of bloodflow to the limb or body part | Nerve | Loss of [NSA](#neural-system-accumulation) and function of the limb or body part |
| Muscle   | Loss of function of the limb or body part. | |{.no-table-head}

* It has to be noted that, out of all organs, bones are unaffected by the lack of bloodflow and oxygen.

## Pain

Although not an actual, physical damage by itself, pain will make injuries much more difficult to manage. A patient who is in pain will be unable to focus on task at hand as well, be slowed down, collapses, drop whatever may be on their hand, and even black out unconscious at time.
* Pain can be managed by using painkillers and other opioids, be careful of [NSA](#neural-system-accumulation).
* To mediate the pain for surgery, the patient can be put to sleep by means of [anesthesia](/guides/medical-guides/Guide-to-Surgery#preparing-the-patient) or [Soporific]().
* If the pain is too high, a patient may black out unconscious for a period of time.

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
* <div><img src=/game_sprites/medhudstates/hudhealth100.gif class="w-16 h-2.5 object-cover object-top">: 100% healthy</div>
* <div><img src=/game_sprites/medhudstates/hudhealth80.gif class="w-16 h-2.5 object-cover object-top">: less than 100% health</div>
* <div><img src=/game_sprites/medhudstates/hudhealth60.gif class="w-16 h-2.5 object-cover object-top">: less than 70% health</div>
* <div><img src=/game_sprites/medhudstates/hudhealth40.gif class="w-16 h-2.5 object-cover object-top">: less than 50% health</div>
* <div><img src=/game_sprites/medhudstates/hudhealth25.gif class="w-16 h-2.5 object-cover object-top">: less than 30% health</div>
* <div><img src=/game_sprites/medhudstates/hudhealth10.gif class="w-16 h-2.5 object-cover object-top">: less than 18% health</div>
* <div><img src=/game_sprites/medhudstates/hudhealth1.gif class="w-16 h-2.5 object-cover object-top">: less than 5% health</div>
* <div><img src=/game_sprites/medhudstates/hudhealth0.gif class="w-16 h-2.5 object-cover object-top">: less than 0%, this is also known as "in critical stage"</div>
* <div><img src=/game_sprites/medhudstates/hudhealth-100.gif class="w-16 h-2.5 object-cover object-top">: the patient is dead</div>

Additionally, the health HUD also display other information for the person, such as whether they are bleeding, if they are infected with a virus, for example. This still shouldn't be fully relied on, as the best way to check someone is with a [health scan](#health-scanner).

#### Heart Rate
Additionally, another way of seeing if a person is stable or not is to look at their heart rate. Heart rates are measured in Beats Per Minute or `bpm` on the scanner. 
* The average healthy bpm is around 80 bpm, anything lower than 60 or higher than 100 bpm are abnormal.
* This method is still highly unreliable, since a lot of chemicals affect the heart rate, including some types of drugs or smokes.

#### Body Temperature
Although not a general indicator of something, body temperature can tell us if someone is dead, affected by chemicals, or is currently on-fire or burning from inside out. This is also present on the medical scanner.
* A body temperature of 0 degrees means death, or that the person is not an organic being.
* A low body temperature is a good indicator of poison, or otherwise toxin dispensed by various spiders within the colony.
* A high body temperature is a good indicator that someone is, or was previously, set on fire. Additionally some toxin will cause this.


### Diagnosis

In general, examining a person by looking will tell you a lot about their condition. Occasionally however, further steps are needed to diagnose the patient outside of what you see and hear.

#### Health Scanner
A handheld [health analyzer](#health-analyzer) can be used to give a lot of information on the patient, this includes things one cannot see or hear such as blood level, toxin level, what and how much chemical is in the patient's blood, radiation damage, and even genetics damage.

#### Full-body Scan
A [body scanner](#body-scanner) can give the most detailed explanation of the patients state compared to a health analyzer down to each individual bones and organs. This is extremely useful as a medical personnel to be able to determine the next cause of treatment.

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
* If a [stasis bag](#stasis-bag) is available, it might be a good idea to use them on a critically injured patient to stop them from getting worse.
* An initial treatment using available medical supply may be wise, as it extends the time you have to transport the person.

### Movement Methods

In the case that a person is able to walk still and conscious, using the `PULL` action on them is safe and allow for quick and mobile movement.

However, this gets complicated when a person becomes dead, incapacitated, or unconscious. By performing a `PULL` option on the injured at this stage, dragging them along the floor will make wounds worse and cause constant brute damage to them.
* Using a roller bed or a movable office chair will allow for safe and quick transport of the patient.
* Putting them in a bag (such as body bag or [stasis bag](#stasis-bag)) will also work.
* Using a `GRAB intent` option will cause you to slow down a bit, but this is considered safe if no option is available.


## Reviving the Dead

Rarely, you'll find yourself with a dead patient. When a patient dies, all their bodily function cease and they begin to slowly decay overtime; blood stops flowing and the organ starts to slowly die. Simply put; the body will begin to rot and get worse the longer they are dead.

This makes the difference between newly deceased person and one that deceased for a long or unknown amount of time very different. As always, execute precautions when transporting the patient and call out for assistance if needed.

### Resustication

Despite death, resustication is always possible. A timer is started on death which determines when their brain decay and when resustication is not possible without surgical intervention.
* Past 15 minutes, the brain starts to decay and take damage.
* Past 30 minutes, resustication is not possible with out [surgical intervention](/guides/medical-guides/Guide-to-Surgery#resustication-preparation) by applying [nanopaste]() to repair the brain.

### Stasis

There is, however, a way to completely halt the degradation of patient's health and practically stabilizing them by stopping all their bodily function. 

This is called stasis, and it works to stop a patient in critical stages from death as well as stopping body from rotting past resustication timer. There are two way to put someone in a stasis.
* [Cryogenics tube](#cryogenics-tube) when set up correctly and paired with [Cryoxadone]() or [Cronexidone]() can be used to put someone in an indefinite stasis state.
* Disposable [stasis bag](#stasis-bag) can be used to store someone inside, this effects slowly wane off eventually, and should be used for transport.

# Administering Medicine

There are a multitude of ways to administrate medicine, each with its own complication, pros, and drawbacks. As a general note, when administering medicine, you yourself should not be panicking, and precaution or confirmation should be made before the administration.

## Oral, Injection, and Touch

Medicine comes commonly in three forms; pills, bottles, and coating within gauzes. 

### Oral Application

This refers to the act of taking a pill, sipping medicine from a bottle, or otherwise eating food injected with chemicals. The chemical goes to the stomach, where it slowly absorbs into the blood, before it is processed within the body. 

This is called metabolism, and each medicine will have a different metabolism rate. In general, the absorbtion rate of the stomach is slower than how fast the body actually process. 

Essentially, you're creating a bottle neck where medicine is slowly introduced into blood. This is useful for a few situation
1. Oral application is extremely quick and easy, requiring no skill or training.
2. Oral application allows for medicine to be absorbed slower, lessening the risk of [overdose](#overdosing) and the rate of which [NSA](#neural-system-accumulation) is gained.

However, oral application also comes with some downsides.
1. The medicine is less effective overall, since it can only be processed as fast as the stomach can absorb it.
2. Occasionally, the total dosage needed isn't even near the overdose threshold at all, costing time and raising [NSA](#neural-system-accumulation) if another chemical needs to be introduced soon after.
3. Pills are harder to manage dosage wise, requiring a [chem master] to produce exclusively.

### Injection

This refers to the act of injecting someone with medicine into the bloodstream using some types of [syringe](#syringe), needles, or [IV drip](#intravenous-therapy-iv). This is generally the most common way of administering medicine.

For syringes and most other types of injectors, the dosage administrated is usually in 5s at a time. Most of these equipment barring the [autoinjector]() requires some basic knowledge of biology.
1. Injection dosage can be easily managed in 5 at a time, making it more flexible than pills.
2. Injection allows the chemical to go directly into the bloodstream, shortening the time it takes for the chemical to be processed.

Downsides for injection is low, but not uncommon.
1. It is very easy to accidentally over-inject someone with medicine, causing an [overdose](#overdosing).
2. The ease of administering and the speed of which medicine is injected allow for multiple medicine to be quickly administered full-amount at the same time, causing high [NSA](#neural-system-accumulation) rates.

### Touch-based Application

The rarest of the three, touch-based application refers to medicine that works better or exclusively works when it comes in contact with skin. You're generally going to find this in the form of gauze soaked with antibiotic, and much more rarely via liquid splashing.

## Overdosing

Overdosing is when a certain chemical type accumulates much more than the body can process, with a numbered maximum threshold before an overdose counted in unit `u`. Overdosing can cause toxin build up, organ poisoning via accumulation, or even strong side effects in some medicine.
* Generally you want to avoid overdosing someone as much as you can, unless you know what you're doing.
* In stronger stimulants and medicine, this could mean organ damage or death, or a build up of pain and toxin.
* In the case that an overdose happens, the person must be purged of the chemical via use of a [sleeper](#sleeper) or [purging chemicals]() immediately otherwise they will suffer from the side effects.

Each chemicals have different side effects from overdosing, some medication overdose are even desirable as it makes them stronger despite the side effect. For more guide on each chemicals overdose threshold, see [Guide to Chemistry](/guides/medical-guides/Guide-to-Chemistry).

## Addiction

Addiction is caused by a prolonged use or overdosing of certain chemicals. Certain drugs, medicine, stimulants, and even toxin has a chance to cause addiction. 
* While under an addiction, the body may suffer some stat debuffs, complications, or even struggle in some otherwise normal tasks.
* A good way to quickly remove an addiction is through the use of [Addictol]() or quickly purging any addicting chemicals left in the body via the use of a [sleeper](#sleeper) or various [purging chemicals]().

## Neural System Accumulation

Neural System Accumulation or NSA refers to the ability of the body to handle storng chemicals or multiple chemicals at the same time. With a general baseline of `100` and a display of `0/100` on the medical scanner.

NSA are raised when chemicals are injected into the body, each coming with different NSA count and stacking if more chemicals are in the body at the same time. A person cannot have 6 different chemicals running at the same time without some side effects.
* An NSA count that is above the patient's limit will slowly cause pain, vomit, hallucination, progressing into bloodied cough, heart attack, and paralysis if an extreme amount of NSA is reached.
* NSA is dramatically lowered when the patient loses their nerve organ to damage, effectively halving the amount of chemical they can process at one time.
* NSA can be raised or lowered with the [Vivification]() stat and the [Cognition]() skill, making each person different in terms of their NSA threshold.
* A higher NSA threshold additionally gives the person more chance to become addicted to addicting reagent, while a lower NSA threshold person is less likely to.

A good way to quickly lower someone's NSA count is by removing chemicals within their blood, this can be through the use of a [sleeper](#sleeper) or various [purging chemicals]().

## Intravenous Therapy (IV)

Intravenous Therapy, or IV, is the process of slowly administering blood or medicine through gravity-assisted needle. The patient has to be attached to an [IV bag]() hanging on the [IV stand](). This allows them to have `1u` of medicine or blood injected into them at a time, over time.

This is the most common way of giving blood to the patient, and can be done by `left clicking` on the IV stand with the IV bag of choice before `left clicking` and `dragging` the IV stand onto the patient next to it. 
* Be careful not to have them move or the needle will be rippedo ut painfull!.


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
  * If left untreated, a sharp wound will start to [swell](#swelling) before turning into an [infection](#infection).
  * Sharp wounds require either [brute treatment kit surgery](/guides/medical-guides/Guide-to-Surgery#internal-organ-repair) or medicine with a stronger brute healing or blood clotting property.

### Swelling

<span style="color: salmon;">Swelling</span> is the consequence of leaving an open internal wound untreated, causing bacteria to form. The area will be painful to touch, and leaving it untreated will cause an infection.
* Swelling takes the form of swelling or abcess of the organ or body part.
* Swelling can be treated before it becomes infected using antibiotics such as [Spaceacillin]()

## Burns and Necrosis

### Internal Burns

<span style="color: orange;">Burn wounds</span> are caused by excessive burn damage. This will cause internal burns on the organ or limb, progressing into an [infection](#infection) if left untreated.
* Internal burns take the form of scorched tissue, charred tissued, or incinerated flesh.
* Internal burns can be stabilized using [Inapprovaline](), but this does not treat it.
* Internal burns can be treated before it becomes infected using [burn treatment kit surgery](/guides/medical-guides/Guide-to-Surgery#internal-organ-repair), [cutting out the damaged tissue](/guides/medical-guides/Guide-to-Surgery#damaged-tissue-and-necrosis-removal), or [Trypsin]().

Once treated, internal burns will left a scarring of [necrosed tissues](#necrosis), which will need to be treated further.

### Necrosis

<span style="color: grey;">Necrosis</span> are divided into two types; damaged tissues which slowly progress into necrosis. Both of which causes pain for the patient and if left untreated, will progress into an [infection](#infection).
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
* Minor poisoning makes the organ much less efficient, requiring more blood, oxygen, and nutrient.
* Accumulation causes much more pain than the other two.

Heavy poisoning are exclusively caused by an overdose of strong medicine or drugs, inorganic compound, and plasma toxicity. Only rarely will you see heavy poisoning, but it is a great indication that something was greatly mis-handled. 

Heavy poisoning of all type causes pain, makes organs much less efficient, and cause them to bloat and take more space. Eventually, heavy poisoning will kill the organ.
* Toxin accumulation and chemical poisoning are noted with the type of toxin or chemical that is poisoning the organ.
* Only organs that are targeted by the medicine will be affected by heavy poisoning, such as [Imidazoline]() overdose causing poisoning in the eyes.
* Heavy poisoning caused by plasma, or plasma toxicity, can be cured using [Carthatoline]().
* Outside of plasma toxicity, no current method is available for curing heavy poisoning, and an [organ transplant](/guides/medical-guides/Guide-to-Surgery#organ-transplant) is required.

## Foreign Objects

Foreign objects refer to inorganic or otherwise foreign objects inside one's body that may be unwanted or actively causing harm. There are three types in general; implants, shrapnels, and biological.

### Implants
Implants can be wanted or unwanted, by default, implants will show up on the [body scanner](#body-scanner), but the specifics will require opening the patient up to examine.
  * Core implants, such as psionic organ, nanogate, and cruciforms, are always detailed on the body scanner, requiring no further opening.
  * Some implants are helpful, such as death alarm, freedom, etc. while others are cause of alarm, mainly the "[Excelsior]()" mindslave implant.
  * Implants can be removed via [surgery](/guides/medical-guides/Guide-to-Surgery#implant-installationeand-extraction).

### Shrapnels
Shrapnels are extremely dangerous debris caused by lodged bullets or explosions from fragmentation mine or grenade. These are metal in nature, and will cause extreme harm in the person until it is removed.
  * Any limbs can be affected by lodged shrapnel, the shrapnel damages the internal organ of any person moving around with them lodged inside. [Splint](#splint) and [roller bed](#roller-bed) is heavily recommended when transporting the patient.
  * Shrapnel can be removed using [shrapnel removal surgery](/guides/medical-guides/Guide-to-Surgery#shrapnel-removal).

### Other Foreign Objects
Sometimes you'll run across different type of nasty, and strangely horrifying foreign objects in your patient's body. Whether it is an active cluster of unknown egg sac, a live spider crawling under their skin, or strange pulsing mass, you must be prepared to remove them.
  * Foreign objects are usually extremely dangerous and harmful, requiring [surgery](/guides/medical-guides/Guide-to-Surgery#foreign-object-removal) in order to get rid of the object.
  * Althought atypical but possible... some human-made object can be accidentally or purposefully sealed inside of one's body too.


## Tumors

<span style="color: salmon;">Tumors</span> are a result of unstable cells mutating from [genetics damage](#genetics-damage). Tumors start slow, but can potentially spread everywhere and kill your patient.
* There are two types of tumors; benign which is not lethal yet still harmful, and malignant which is extremely dangerous.
  * A fully developed benign tumor will not kill you, but cause the limb and organ to be much less functional.
  * A fully developed malignant tumor will start killing your organ, spreading once it has killed an organ.
* Tumors start slowly from a polyp stage, slowly developing into a full grown tumor after a period of time.
  * They may also be seen as neoplasma or strange growth.
* Tumors will continue to grow, even when the patient is dead. This makes leaving a tumor growing in a corpse without stasis a **very** bad idea.

Tumors can be treated in one of the following ways.
* [Manual surgical incision on the organ](/guides/medical-guides/Guide-to-Surgery#tumor-removal).
* [Peridaxon](), [Hyronalin](), and [Cryoxadone]() will get rid of all tumors in the polyp stage.
* [Rezadone](), [Ryetalin](), and [Cronexidone]() will get rid of all tumors in the fully grown stage.


## Bone Wounds

Bone wounds are types of [damage to the bone](#fractures), this may not be fractures but simply damages that causes constant pain to the patient. All types of bone fixing requires [surgery](/guides/medical-guides/Guide-to-Surgery#bone-setting-and-repair).
* Bone damage caused by blunt application of force may take shape in burising, sprained ligament, or dislocation, and will require the use of [bone setter]().
* Bone damage caused by sharp weapons may take shape in perforation, cavitation, puncture, laceration, avulsion, or chipped tissue, and will require the use of [osseous tape]() or other adhesives.
  * Both types of bone damages can be repaired like other organs using a brute treatment kit.
  * [Ossisine]() works to mend the bones in this stage.
* Genuine fracture, aka the breaking and detachment of two bone pieces, however, require the use of [bone gel]() or the overdosing effect of [Ossisine](). As mentioned before, this will damage internal organs without the use of splint.

## Organ Scarring

Organ scarring is an effect caused mostly by overdosing on stimulants and other strong toxins. By it self it does not spread, but cause pain and damages the organ. An organ may be spotted with scar tissues, which is different from [necrosis](#necrosis).
* The only treatment currently is a strong does of [Trypsin]().

---

# Medical Equipment

> This area is currently Work in Progress.
{.is-warning}

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