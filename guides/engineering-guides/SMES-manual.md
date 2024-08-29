---
title: SMES and RCON Manual
description: Operating and setting power distribution in the colony.
published: true
date: 2024-08-29T05:14:30.835Z
tags: guide, engineering, engineering guide, wiki: needs revision, wiki: missing file, wiki: outdated
editor: markdown
dateCreated: 2024-08-29T05:14:30.835Z
---

> This article is ported directly from [Sojourn Wiki](https://sojourn13.space/wiki/).
{.is-info}
# SMES Overview
`[SMES.png]` **SMES** stands for the *Superconducting Magnetic Energy Storage*. It's a device used to store electrical power. 

While SMES units are very effective, they are also expensive, requiring high end circuit board and expensive parts. SMES units may be upgraded to increase their capacity and/or maximal input/output levels. 
* If you need to quickly replace the SMES you may try using cheaper but less powerful **Cell Rack PSU** instead.

## SMES Configuration
SMES units may be configured via interface which is opened by left-clicking with empty hand on the SMES. Alternatively you may use the [RCON console](/guides/engineering-guides/SMES-manual#rcon) to operate most SMESs on station. The interface looks like this: 

![smes_gui.png](/smes_gui.png)

### Input
Each SMES needs terminal to operate properly. This terminal allows you to charge the SMES from one power network, and output into another one. By using apropriate controls in the GUI you may set any input value up to certain cap. 

This cap can be increased by upgrading the SMES unit, as [described further in this guide](/guides/engineering-guides/SMES-manual#upgrading-smes). Also, please note that setting larger input than available will cause the SMES to enter "Partially Charging" state. This means the SMES is still charging, but not at set input rate. You may choose from two input options - `OFF` and `AUTO`. 

### Output
The SMES outputs power into wire placed directly under it. Usually, you want to keep output lower than input, however sometimes you may have to increase output to compensate for larger demand. This is common with main Engine SMES when setting up Substations. The output rate is also capped and also upgradeable. You may choose from two output options which are self explanatory - `ONLINE` and `OFFLINE`. 

### Values
> [**Outdated Article**](/maintenance/Templates#outdated): This section is **out-of-date**, **incomplete**, or **not currently in the game**. **Reason**: This is the old substation setting for the old Sojourn Colony map. If updating is not feasible, removal is welcomed for the substation part.
{.is-warning}

These are suggested example settings for few SMESs around the station. You may choose different settings, depending on available power and other factors. Try to consult the Guild Master when unsure. 

#### Main Station Settings
| Location | Input | Output | Notes
| - | - | - | - |
| Engine Room SMES | 250 kW, Auto | 250kW, Online | This is mostly if you're running an engine like the [Antimatter Engine](/guides/engineering-guides/Guide-to-Power), [TEG](), or [Supermatter](). You want the Engine SMES to be charged to ensure cooling will remain operational. 
| Main SMES | 1000kW, Auto | 950kw, Online | You may have to lower the input if total power generation is producing less than 750kW. On the other hand, if it's producing more increase input. 
| Atmospheric SMES | 250kW, Auto | 250kW, Online | Some things, especially pumps, use large amounts of power. This means atmospherics needs a lot of power. 

#### Substation Settings

<details>
  <summary>
    Substation Settings
  </summary>
  
  | SMES | Input | Output | Notes
  | - | - | - | - |
  | Cargo | 40kW | 80kW | Powers the cargo department. Normally draws 8 kW, has 1 recharger. 
  | Civ West | 40kW | 80kW | Powers surface EVA, tool storage, and first aid station. Normally draws 7 kW, has 2 rechargers. 
  | Civilian | 80kW | 160kW | Powers laundry room, holodeck, cryo pods, and library. Normally draws 32 kW, can raise higher than 80 kW if holodeck is in use. 
  | Command | 60kW | 120kW | Powers bridge, CD and HoP offices, teleporter, meeting room, IAA office, and EVA. Normally draws 18 kW, has 3 rechargers and 1 cell charger. 
  | Engineering | 80kW | 160kW | Powers the engineering department, including the three space-side telecomms relays. Normally draws 37 kW, has 4 rechargers and 3 cell chargers. 
  | Medical | 100kW | 200kW | Powers the medical department. Normally draws 36 kW, has 2 rechargers and 1 gas cooler. Given high input due to value to the facility. 
  | MedSec | 40kW | 80kW | Powers surface triage and surface drunk tank. Normally draws 8 kW, has 1 recharger.
  | Mining | 40kW | 80kW | Powers the mining department. Normally draws 7 kW, has 1 recharger and 1 cell charger. 
  | Research | 100kW | 200kW | Powers the research department. Normally draws 46 kW, but has a lot of different rechargers, hence the high input. 
  | Science Outpost | 40kW | 160kW | Powers the toxins outpost. Normally draws 15 kW, but houses atmospherics equipment which can increase power usage greatly. Otherwise it is mostly unused. 
  | Security | 40kW | 160kW | Powers the security department. Normally draws 32 kW, has numerous wall rechargers. 
  | Surface Civilian | 60kW | 120kW | Powers hydroponics, the bar and kitchen, reading rooms, plasma shelter, and backup shuttle landing pads. Normally draws 23 kW, has 1 cyborg recharger. 
  | Telecomms | 60kW | 120kW | Powers surface telecommunications. Normally draws 22 kW. 
  | Mining Station | 250kW | 250kW | Powers the off-station mining outpost. Normally draws 5 kW, has 1 recharger, 1 cell charger, and 1 mech charging station. Maxed input is for miners to turn on the PACMAN to power the SMES. 
  | AI Chamber | 200kW | 200kW | Powers the AI Core. Normally draws 10 kW, but increases to 60 kW if an AI is present. This SMES cannot be accessed remotely. 
  
</details>

## SMES Failures
> [**Needs Revision**](/maintenance/Templates#needs-revision): This section may be **outdated or incorrect**, once verified this tag should be removed or replaced with relevant [tags](/maintenance/Templates#maintenance-template).
{.is-info}

Disabling failsafes, as outlined in [Hacking section of this page](/guides/engineering-guides/SMES-manual#hacking-smes) may cause SMES Failure when removing the components (crowbar step), or adding new components (inserting new coils). 

Chance of a bad outcome happening is directly proportional to SMES charge percentage. 
* SMES charged to 75% has 75% probability of failing, etc. If this failure happens, effects are once again related to charge percentage.

| Type of Failure | Charge Percentage | Description
| - | - | - |
| Discharge | Any | The SMES will lose ALL it's remaining charge.
| Sparks | Any | Mostly harmless, some sparks will fly from the SMES, potentionally igniting fire if flammable material is nearby.
| Electrocution | Any | Shocks the user. Please note that while insultated gloves mitigate the effect, they aren't guaranteed to 100% protect you. Damage scales with charge percentage. Anything above 60% charge is instant-kill even with gloves.
| EM Pulse | Above 15% | Causes electromagnetic pulse which breaks nearby electronics. This usually trips fire alarms, breaks consoles, and may even kill/injure the AI/cyborgs/people with prosthetics depending on situation. Size of EM Pulse is proportional to amount of stored power.
| APC Overload | Above 35% | Overloads lighting circuits of few APCs connected to the SMES's output. Please note that having something between the SMES and APC (such as, another SMES) will prevent the damage. Chance is proportional to amount of stored power.
| APC Failure | Above 35% | Completely breaks few APCs in SMES's output. Same rule as above applies.
| Magnetic Containment Failure | Above 60% | The worst thing that can happen. If SMES's magnetic containment fails remaining charge is released in form of violent explosion. The SMES is completely destroyed, as well as few nearby tiles. This almost always causes hull breach, and the explosion may gib you. After this failure is triggered you have 30-60 seconds before the SMES blows up.

## Hacking SMES
MES units may be hacked to enable or disable various features. Remember to wear your Yellowgloves.png protective equipment or risk injury. 
* To access the wiring open front panel with screwdriver. Then click the SMES with empty hand to open up wiring window. There are five wires, which have randomized colours every round.

| Wire | Detail |
| - | - |
| Input | Cutting this will cause the SMES to stop inputting. Pulsing will temporarily disable input.
| Output | Cutting this will cause the SMES to stop outputting. Pulsing will temporarily disable output.
| RCON | Cutting this will disable RCON (Remote CONtrol), hiding the SMES from control consoles. It also disables AI control. Pulsing does nothing.
| Failsafes | Cutting will allow you to modify the SMES even if it is charged. Please note that this may result in catastrophic overload if charge is large enough. Pulsing does nothing.
| Grounding | Cutting or pulsing this wire will overload the SMES, causing quick dissipation of stored energy. This energy may however damage or destroy APCs in output power network, so it is advised to either disconnect the SMES, or at least use Substations configuration to prevent damage to many APCs. Mending will restore grounding and stop the overload. This is highly similar failure of charged SMES, but with less risks involved for the user. Remember that doing this as non-antagonist is not a good idea.

## Construction and Deconstruction

<details>
  <summary>
    Constructing an SMES
  </summary>
List of Material; 5 metal sheets, at least 35 cable pieces, SMES Circuit Board, at least one Superconductive Coil (any type)
  
  <h4>Construction Step</h4>

1. Use your metal sheets to build machine frame.
1. Use your cable coil on machine frame to add wires.
1. (OPTIONAL) place wire under the machine frame. The SMES will output into this wire.
1. Use your SMES Circuit Board on wired machine frame.
1. Add 30 pieces of cable (one full length cable coil).
1. Add one superconducting magnetic coil.
1. Finalise the SMES with screwdriver.
</details>

<details>
  <summary>
    Attaching a Terminal
  </summary>
New SMES starts without a terminal which is used to directly access it. Furthermore, terminals may be damaged by explosions or similar effects. Fortunately, installing new terminal is easy. 
  
1. Open interface of your SMES and turn it's input and output OFF.
1. Use screwdriver on the SMES to open the cover.
1. Use cable coil on the SMES to add new terminal. You need 10 pieces of cable for this. If you make a mistake use wirecutters to remove the terminal and repeat this step.
1. Use screwdriver on the SMES to close the cover.
  
</details>

<details>
  <summary>
    Deconstructing an SMES
  </summary>
  <h4>Preparation</h4>
  
1. First of all you should **ensure the SMES is discharged**. While there is a workaround, it **will** cause an injury and/or damage.
1. Open the SMES's interface by left clicking it. Ensure both Input and Output are turned Off.
1. Use screwdriver on the SMES to open the access panel.
1. Use wirecutters on the SMES to cut the terminal. If the terminal is missing (or destroyed) simply skip this step.
  
  <h4>Deconstruction Step</h4>
  
1. Complete everything in Preparations
1. (OPTIONAL) Use multitool on the SMES to disconnect safety circuit. This step may be skipped if you completely discharged the SMES. **DO NOT PROCEED IF SMES IS CHARGED ABOVE 50%**, usually, anything below 15% is safe (with gloves). Anything above 50% is likely to kill you.
1. Use crowbar on the SMES to begin removing the components. This may take up to 60 seconds, depending on amount of coils in the SMES. Basic SMESs should take approximately 10 seconds. SMES will turn into machine frame and few components. You may use these components for research or for repairs/upgrades.
1. Use wirecutters to remove cables from the machine frame.
1. Use wrench to dismantle the machine frame.

</details>
  
  
## Upgrading SMES

There are three types of coils in existence:
* **Superconductive Capacitance Coils** highly increase the amount of energy the SMES can store.
* **Superconductive Transference Coils** highly increase the maximum input and output rate.
* **Superconductive Magnetic Coils** increase both storage and transfer rate, but at a lesser extent.

There are two of each type of coils in the Engineering Hard Storage, in one of the crates.

---
When building an SMES you may add only a single Magnetic Coil into it. However, you may add up to five more coils later. This process is slightly more complex than terminal replacement.

1. Ensure the SMES is discharged. Alternatively, you may disable the failsafes (see point 4.). Please read the "SMES Failure" section of this guide before proceeding.
1. Open interface of your SMES and turn it's input and output OFF.
1. Use screwdriver on the SMES to open the cover.
    *(OPTIONAL) Disable failsafes by cutting the correct wire [(see Hacking section)](/guides/engineering-guides/SMES-manual#hacking-smes).*
1. Use your superconducting magnetic coil(s) on the SMES to install them.
    *(OPTIONAL) Re-enable failsafes if you disabled them.*
1. Use screwdriver on the SMES to close the cover.

# RCON
**RCON**, or **Remote CONtrol**, allows remote operation of all SMESs from RCON console. To allow usage of RCON you have to set an RCON tag. **This tag has to be unique (ie. do not use tag already used by another SMES).**
* To set new tag click the SMES with multitool and type in the new tag. 
* If you wish to disable RCON you may either cut apropriate wire [(see Hacking section)](/guides/engineering-guides/SMES-manual#hacking-smes), or use tag "NO_TAG".

![rcon1.png](/ingame_screenshots/rcon1.png)

## RCON Breakers
Bypass breakers directly shunt the main grid's full power into their respective areas. This is useful when the SMES is damaged or destroyed, or the power line is cut.
* The direct transfer can result in people losing limbs from tripping over exposed wires and or APCs to arc if the energy in the main grid is too much..

![rconbreaker.png](/ingame_screenshots/rconbreaker.png)