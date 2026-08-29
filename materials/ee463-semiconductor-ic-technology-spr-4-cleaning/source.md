---
title: "EE463 Semiconductor IC Technology  Spring, 2010"
created: 2026-08-29
updated: 2026-08-29
tags: [material, source]
source: "원문 텍스트 (그대로 보존) → Issue #68"
kind: material
source_issue: 68
---

# EE463 Semiconductor IC Technology  Spring, 2010

### 머리글

1
Controlling unwanted impurities
Modern IC factories employ a three tiered approach
to control unwanted impurities:

### 1 Clean rooms

• Building chips in a clean environment

### 2 Wafer cleaning

• Chemically clean the wafers often and thoroughly

### 3 Human control

• Minimize the number of people working in the clea

2
SIA Roadmap
Actual numbers are different from today’s data because there were many changes since the table
was made. Nevertheless, you can get the general feeling about the requirement.
LLS : Localized Light Scattering
GOI : Gate oxide Integrity

3
Basic concepts
Contaminants may consist of particles, organic
films (photoresist), heavy metals or alkali ions

4
Examples
Example #1: MOS VTH is given by:
If tox = 10 nm, then a 0.1 volt Vth shift can be caused by Q
M
= 6.5 x 10
11
cm
-2
(< 0.1% monolayer or 10 ppm in the oxide).
• Example #2: MOS DRAM
Refresh time of several msec requires a generation lifetime of
σ: capture cross section of the trap (~ 10
-15
cm
2
),
vth : minority carrier thermal velocity (~ 10
7
cm/sec)
This requires N
t
(trap density) ~ 10
12
cm
-3
or ~ 0.02 ppb (see text).
These traps are normally associated with deep level impurities (Au, Cu, Fe, etc)

5
Level 1 Contamination Reduction: Clean Factories
• Air quality is measured by the “class” of the facility.
Class X means that in each cubic foot of air in the factory, there are less than X total
particles greater than 0.5μm in size
• Typical office building is about class 100,000. State-of-the-art clean room is class 1.

6
Level 1 Contamination Reduction: Clean Factories
• Factory environment is cleaned by:
‒ HEPA (High Efficiency Particulate Air) filters and recirculation for the air,
‒ “Bunny suits” for workers.
‒ Filtration of chemicals and gases.
‒ Manufacturing protocols.

7
Level 2 Contamination Reduction: Wafer Cleaning

8
RCA clean is “standard process” used to remove
organics, heavy metals and alkali ions

9
Modeling Wafer Cleaning
• Cleaning involves removing particles, organics (photoresist) and metals from wafer
surfaces.
• Particles are largely removed by ultrasonic agitation during cleaning.
• Organics like photoresists are removed in an O2 plasma or in H2SO4/H2O2
solutions.
• The “RCA clean” is used to remove metals and any remaining organics.
• Metal cleaning can be understood in terms of the following chemistry.
• To remove metal atoms from the surface of a Si wafer, they need to be converted
into ions that are soluble in the cleaning solution.
• This process involves oxidizing the metal atoms.
• Oxidation is defined as a process that removes electrons from an atom, while
reduction is the opposite process in which an atom gains electrons.

10
Oxidation-reduction reactions
Stronger oxidants have more negative oxidation potential.
H2O2/H2O reaction will dominate Fe3+/Fe reaction because of stronger oxidation potential.
Then, H2O2 takes electrons from the metal atoms, creating ions.
General rule is, the lowest reaction in the table dominates, going to the left and driving all
reactions above it to the right.
• Fundamentally the RCA clean works by using H
2
O
2
as a strong oxidant.
