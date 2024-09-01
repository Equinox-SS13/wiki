---
title: Guide to Atmospherics
description: Pumping, siphoning, and making sure your neighbor is breathing the right air.
published: true
date: 2024-09-01T14:04:27.970Z
tags: guide, engineering guide, wiki: needs revision, wiki: work in progress, engineering
editor: markdown
dateCreated: 2024-09-01T14:03:22.816Z
---

> [**Needs Revision**](/maintenance/Templates#needs-revision): This article or section may be **outdated or incorrect**, once verified this tag should be removed or replaced with relevant [tags](/maintenance/Templates#maintenance-template).
{.is-info}

# All About Atmospherics
What is Atmospherics? Atmospheric covers the subject of gas and many extensions of it and is a subject many engineer should at least know the basic of. 
* This includes the distribution of breathable air, firefighting, and generation of power using gas as a form of coolant or combustion.

## Gases in the Air
There are many types of gas, some breathable, some toxic, some combustible. It is up to the engineer and their devices to identify the content of the air in a local area.

| | |
|-|-|
| Nitrogen (N2) | Nitrogen is one of the component in a typical breathable Air mix. Being naturally colder, N2 soaks up heat in the air and lowers the temperature of an on-going fire to the point where the flames self-extinguish if enough of it forms up the content of the area.
| Oxygen (O2) | Oxygen is the lifeline of all organism. You breathe this, and running out of it will cause your slow death by [suffocation](/guides/medical-guides/Guide-to-Medicine#oxyloss). O2 is the reason fire can burn, without it, fire will extinguish itself if no O2 is present. Having less than 16 kPA of O2 will suffocate you.
| Air Mix | The general name of breathable atmospheric air composed of 79% N2 and 21% O2.
| Carbondioxide (CO2) | An invisible heavy gas that is the byproduct of fire and breathing, living thing. CO2 suffocates people quickly, and is one of the first gas to be scrubbed out from within the station.
| Nitrous Oxide (N2O) | An industrial gas used combined with O2 in Medical as a form of Anesthesia notable by it's white-fleck. Makes you laugh at low doses, sleep in higher doses. It is significantly harder to be scrubbed/filtered out compared to other gas.
| Plasma | Plasma in gas form easily spotted by the purple-fleck, equally as toxic and dangerous as liquid form. Plasma is a very efficient fuel for fire to burn and expand rapidly with the heat, but it cannot burn if no O2 is present.
| Burn Mix | Burn mix usually refers to a mixture of plasma and O2; an efficient fuel and firestarter, causing a very high-pressure, long-burning high temperature gas.

## How Gas Works

### The Gas Law

Gas operates off of the formula: `PV = nRT`

In layman term, pressure and volume is increased when temperature rises, and decreases if the opposite occur;


`T (Temperature)` - Temperature is measured in Kelvin with the formula conversion to Celcius of *(K = C + 273.15)*. 273.15 is freezing point, and 373.15 is boiling point.
`P (Pascal)` - Pascal measure the pressure of gas, usually in `kPA`, or Kilopascal *(1000 P per kPA)*
`V (Volume)` - Volume is measured in liters.
`n (Number of Moles)` - Measures the amount of substance of gas, each mole is a substance.
`R (R Number)` - A constant or 8.31.

* More gas can be stored in a room or container when it is super cooled.
* Gas will expand when temperature rises, making rapid rise in temperature (such as fire) cause the gas to expand rapidly. This can cause windows to break, tanks to explode, etcetera.

This applies to engines or machines that uses coolant such as [the Supermatter Engine](/guides/engineering-guides/Supermatter), [Biogenerator](), and  [cryogenics tube](/guides/medical-guides/Guide-to-Medicine#cryogenics-tube) or difference in temperature and pressure such as [Thermoelectric Generator](/guides/engineering-guides/TEG).
<br>

### Notes
* Any gas can displace O2, with O2 less than 16kPA people start to suffocate inside of it.
* Pressures above 750kPA start to give brute damage to people from over-pressure compression, damage increases significantly every 375kPA extra. This can be negated by wearing voidsuits or other space-capable suits
* The reason space does burn damage to one's person is not because of the low pressure, but the low pressure causing extremely low temperature (in space, this is sub 20 Kelvin, or roughly -253 Celcius).
* N2O is invisible at low pressures, check N2O tanks for doctors forgetting to close their valves.

## The Pipes
Within the colony, many pipes, scrubbers, and vents occupy the area. These are controlled locally with an Air Alarm and can be remotely controlled through an Atmospherics Program.
* Pipes can be acquired from a Pipe Dispenser, such as the Disposable Pipe Dispenser in Engineering.
* Pipes can be wrenched into the floor, causing it to connect to the pipe next to it. It can also be covered with a tile if wrenched on an underplating.
* Pipes at higher pressure than 300kPA cannot be unwrenched.

<br>

| Name | Types of Gas Pipes |
|-|-|
| <span style="color: teal;">**Air Supply**</span> | A set of <span style="color: teal;">blue</span> pipe in a loop that sends air to all the vents on the colony. Connected directly by <span style="color: cyan;">cyan</span> and <span style="color: orange;">orange</span> pipes.
| <span style="color: cyan;">**Air Mix**</span> | A set of <span style="color: cyan;">cyan</span> pipes where N2 and O2 mixes into Air inside of Engineering.
| <span style="color: red;">**Air Scrubber**</span> | A set of <span style="color: red;">red</span> pipe in a loop that brings back filtered CO2, N2O, or Plasma back to Engineering.
| <span style="color: orange;">**Custom Mix**</span> | A set of <span style="color: orange;">orange</span> custom air mixing pipe in Engineering where an engineer can inject custom air into facilities.
| <span style="color: lime;">**Injection**</span> | A set of <span style="color: lime;">green</span> pipes that transport a single type of gas inside engineering.

* **Air Pump** - A pump that moves air from one pipe to another, works as a valve. The red-striped side is the direction the pump pumps to. Also useful as a regulator for how much gas can pass through this checkpoint at one time (or rather, an unintended bottleneck).
* **High Power Pump** - A more effective version of the air pump, allowing better pump rates.
* **Valve** - A valve that can open or close, does not bottleneck gas movement unlike the pump.
* **Meter** - A device attached to pipe system that measures the section of the pipe.
* **Gas Filter** - Filters out gas from the main pipe onto the side, letting the rest go through. Potential bottleneck.
* **Gas Mixer** - Like filter, but mixes gas together into a single pipe.
* **Omni Filter/Mixer** - Gas filter/mixer, but the input/output direction can be customized fully on all directions.
* **Heat Exchange** - Equaize the temperature between two pipe networks without mixing the gases together. The two exchange has to be facing each other.
* **Universal Pipe Adapter** - Used to interface between normal, air supply, and air disposal pipes. Making 3 pipes able to be connect to each other.
* **Connector Port** - Connects the pipe network to a canister containing gas.
* **Gas Canister** - Contains gas within a portable tank that can be moved around, leaks out gas when damaged enough times.

---

If you are confused on how each of these things work, this may be a helpful way to think of the pipes: 
* every section of pipes is like a tank that holds gas. The pumps will simply move gas from that "tank" to another "tank", or another section of pipes. 
* There is not a flow through the pipes, just the pumps, filters, and other devices. Opening a valve will link two tanks together to be one tank, and closing it would make them go back to two separate tanks.


### Atmospheric Equipment
* **Vent** - Dispenses breathable air filling the room, stops when the Air Alarm sensors that the pressure is at a desirable level.
* **Scrubber** - Filters out toxic CO2 and Plasma when detected by the Air Alarm sensors.
* **Air Alarm** - Measures the local air system and control the equipment within the room, has alarm thresholds that sends an alarm to Atmospheric Alarm Programs if the threshold is passed, can automatically close emergency shutters.
* **Emergency Shutter** - An air-tight motor-locked door that closes when a fire alarm is pressed or an Air Alarm notice fire or an high or lack of pressure.
* **Fire Alarm** - A manual firealarm that can be pulled, causing emergency shutters to close.
* **Inflatable Barrier** - A quick-drop air-tight seal that can be quickly set up in an emergency.
* **Portable Air Scrubber** - A mobile scrubber capable of quickly filtering out toxins and contaminants in the air.
* **Gas Cooling/Heating System** - Cool or heat the gas in the pipe system respectively using power.

## Air Alarm Control
Air alarms are the central tool of an atmos tech outside setting atmospherics up. To use an air alarm, simply swipe your ID across it. Here's the different options: 

### Panic Syphons: 
Turns all vents off and set all scrubbers to syphon, this rapidly depressurize air from the area. 

### Vent Control: 
* `External on, Internal off`: Drain or add air from the tile the vent is on to make it the correct amount. All air being moved goes into or comes out of the pipe the vent is attached to. Set to 0 to drain air, or pressurise to specific levels.
* `Both on`: Completely useless. Don't bother.
* `External off, Internal on`: Drains or adds air to the tile to get the pipe attached to the correct level. Setting a vent to internal and the desired pressure to 0 causes ALL gas which enters the pipe to be shunted out onto the tile.
### Scrubber Control
* `Scrubbing`: Slowly drain any gasses set to scrub in the air of the tile they are on, and transfer it to their pipe. Really, really slow with N2O.
* `Syphon`: Like scrubbing, but syphoning indiscriminately and drain all gasses on their tile.

## Fire
An effect usually caused by burning fuel such as wood, paper, or even plasma in the presence of Oxygen. It causes massive burn damage, and a strong fire will not be stopped by standard firesuits. 

Fire will ignite any form of combustibles in near tiles. Sufficiently hot fires use less oxygen as they rise in temperature and expand the volume of the gas within the room into multiple folds.

To control a fire, a few things must first be considered;

### Size of the Fire
A localized bundle of burning wood and paperbag or spilled alcohol can be easily extinguished by fire extinguisher, while a bigger atmospheric fire will quickly get out of control. 

Sometimes a quick determination has to be made whether the fire can be quickly extinguished or not--if not, the first step to extinguishing fire is to stop it from spreading.

### Controlling Fire
A variety of air-tight shutters, airlocks, and inflatable barriers can quickly stop gas fire in its track. Any quick-witted colonists can pull the fire alarm, containing fire within the area to slowly burn out of fuel.

Otherwise, any process to restrict fire spread will help. Displacing O2 with other gasses, scrubbing or siphoning the air, or even just waiting it out.
* If the area must be accessed during or after the fire for repair or prevention processes, a makeshift airlock should be created by having two sets of air-tight doors leading to each other to contain the spread of fire or rise of temperature within the following area that will surely boil people and trigger air alarms.
