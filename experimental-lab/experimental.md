# Experimental procedures
**Tutorial paper about cyclic voltammetry and electrochemistry**
[A Practical Beginner’s Guide to Cyclic Voltammetry](https://pubs.acs.org/doi/full/10.1021/acs.jchemed.7b00361)

## Cleaning procedure
Before any glassware can be used for clean electrochemistry, it needs to be cleaned by us thoroughly. We use potassium permanganate to oxidize any organic compounds and dilute [piranha solution](https://www.youtube.com/watch?v=cLpSapjKcxM) (sulfuric acid + hydrogen peroxide) to dissolve any inorganic impurities. The name _piranha_ refers to the similarities with a real piranha when organic material comes into contact with the solution. These chemicals are therefore really dangerous and you should be really careful not to spill and damage your clothes.  
1.	Store glassware in a 1 g/L KMnO4 + 0.1 M H2SO4 solution for 2-3 h.
2.	Pour out KMnO4 solution for reuse into storage vat
3.	Rinse glassware 3x with DI water (dispose of very dilute KMnO4 in sink)
4.	Soak in dilute piranha (~5 mL H2SO4 + ~5 mL H2O2 in 3 L beaker) for 20 minutes
5.	Dispose of dilute piranha by neutralizing with sodium carbonate in a seperate bucket
6.	Rinse 3x with DI water
7.	Boil in DI water 3x

After the cleaning procedure, our glassware remains clean. However, everything else it not clean. In electrochemistry we have to be really careful what touches what. Except for the cleaning procedure, the chemicals we are using are not extremely dangerous. Therefore, gloves are worn more to protect the cleanliness of the experiment than for the safety of ourselves. Therefore we also have to keep our gloves spot clean and only touch the outside of glassware and only use clean glassware (really clean).

Every consumable like glass vials, gloves, pipette tips and centrifuge tubes are made sterile and therefore clean enough for our experiment. We can use these however much we like. Solvent bottles are also clean, and we should make sure they stay clean and avoid cross contamination. 

## Preparing electrolyte solutions
**DO NOT USE UNCLEAN GLASSWARE, DO NOT USE METAL SPOONS, DO NOT USE NEEDLES, DO NOT USE SOLVENT BOTTLES, DO NOT PUT CHEMICALS BACK INTO THE CONTAINERS.**


1.  Make sure you have a clean beaker or flask to measure out the water
2.  Do not use spoons but use clean pipette tips only touched by gloves to weigh out chemicals on clean surfaces and **do not put chemicals back into their packaging**. If you weigh too much, make more solution or dispose in trash/chemical waste.
3.  Only use cleaned glassware and disposable syringes (no needles) to make electrolyte solutions
4.  Make electrolyte directly in the cell

## Catalyst preparation
Prepare two different solutions:
1.  Prepare 5 mL suspension of Carbon black in acetone (0.65 mg/mL). Sonicate the suspension for 30 min
2.  Prepare 1 mL solution of 1.25 mM metal complex in acetone
3.  Wrap the vial in aluminum foil to protect it from the light
4.  Store in the fridge over night

The complex will be diluted in the catalyst ink, for different loadings, you can vary the concentration from 1.25 mM to 3.5 mM.

Make catalyst ink in seperate vial:
1.  Take 40 µL complex solution
2.  Add 20 µL Nafion suspension and homogenize by using the sonicator for 15 min
3.  Add 120 µL Carbon black suspension (sonicate for 10 min. or more prior to application)

Dropcasting:
1.  Polish a graphite rod with rough and smooth sandpaper, polish in a 8 pattern for 30 - 60 s per sandpaper. Rinse with water and wipe with paper afterwards.
2.  Take 5 µL of catalyst ink with pipette and drop bottom of graphite rod
3.  Let acetone evaporate in air for 30 - 60 s
4.  Dropcast a second time
5.  Let it dry for 5 - 15 more min
6.  To clean the substrate after the experiment, for graphite rinse with acetone and repolish with the rough and smoother sandpaper. For gold, sonicate in acetone 15 min. 


## Setting up a three-electrode setup
Setting up the electrochemical cell requires a specific order in order to protect the potentiostat and your working electrode. There is never any potential or current applied to the reference electrode, but it is needed for the potentiostat to 'know' at which potential it needs to keep the CE and WE so we connect the RE first. Then we connect the CE to have a 'sink' for the current to go if the potentiostat needs to get rid of current. When we connect our WE last, the potentiostat keeps the potential vs the RE stable and uses the CE to get rid of current when it needs to. Now when we connect the WE, there will never be any current/potential spike that could potentially be damaging to the electrocatalyst.

```{figure} /images/cell-setup.png
---
height: 300
name: cell-setup
---
A schematic display of the three-electrode setup with a working (WE), counter (CE), and reference (RE) electrode. The numbers indicate the order in which they need to be connected, and the colours indicate which clips are used to connect to the respective electrodes. 2 clips on the potentiostat are unused. 
```

**Always rinse all electrodes with demi water before inserting into the cell**

1.	Fill cell with electrolyte 
2.	Rinse reference (hydroflex) and counter electrode (graphite) and insert into cell
3.	Connect reference electrode
4.	Connect counter electrode
5.	Briefly anneal working electrode (if Gold)
6.  Assemble working electrode
6.	Submerge and connect working electrode 
7.	Make sure no electrodes are touching
8.	Load appropriate potentiostat settings
9.	Connect working electrode
10.	Run measurement

## Cyclic voltammetry (CV)
_Before any measurement measure ohmic drop (iR-drop) using impedance spectroscopy and measure the open circuit potential._
1.  Make sure electrodes are connected properly
2.  Select starting potential should be around 0.8 V. 
3.  Select highest vertex potential: for graphite go to 1.0 V maximum. 
4.  Select lowest vertex potential (should be > 0 V)
5.  Select scan rate (mV/s) in the range of 5 - 250 mV/s
6.  I range (100 micro A), E step to 1 mV
7.  When iR-drop and OCP have been determined, start CA and CV

## Linear sweep voltammetry (LSV)
An alternative to cyclic voltammetry.

1.  Start at a stable potential from which you want to scan
2.  Use chronoamperometry (CA) at a stable potential for 1 min
2.  Follow same steps as CV except for lowest vertex potential

## Chronoamperometry
Applying a constant potential and measuring the current over a long time to estimate the activity and stability. This is usually used once the potential is found where the catalyst produces the highest activity rate. 