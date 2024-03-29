---
title: "RNA_SIP_Protocol"
output: 
  html_document:
    keep_md: true
    toc: true
    toc_float: true
    toc_depth: 6
    code_folding: hide
    number_sections: false
    theme: lumen

knit: (function(input_file, encoding) {
  out_dir <- 'docs';
  rmarkdown::render(input_file,
 encoding=encoding,
 output_file=file.path(dirname(input_file), out_dir, 'index.html'))})
---



This is the Huber Lab RNA SIP protocol that was co-written by Caroline Fortunato, Amy Smith, Sabrina Elkassas, and Olivia Ahern. It was last updated 27 September 2022 by Olivia Ahern. Another version of this protocol, using the old CsTFA formulation (liquid) [can be found on protocols.io](https://www.protocols.io/view/density-gradient-fractionation-of-rna-from-rna-sip-36wgqm1xvk57/v3). 


This protocol is to extract RNA and fractionate from 20% 13C-labelled cultures from Siders Pond into 22 fractions. The experiment that used this protocol can be found [at Olivia Ahern's github page](https://omahern.github.io/Exp4/).  


# RNA Extraction

**Items used in protocol:**

* [0.22 um Millipore express filters](https://www.sigmaaldrich.com/US/en/product/mm/gpwp09050)
* [MasterPure™ Complete DNA and RNA Purification Kit (Lucigen MC85200)](https://www.fishersci.com/shop/products/masterpure-comp-dnarna/NC9801456)


**Before beginning the extraction protocol:**

1.	Turn on the microcentrifuge and turn the temperature to 4 °C. 
2.	Turn on heat block to 65 °C and allow to get to temperature.
3.	Wipe down pipettes and workspace with 10% bleach and 70% ethanol and RNAseZap.

**Cell Lysis**

1.	Dilute 1.15 μL of Proteinase K into 350 μL of Tissue and Cell Lysis Solution for each sample (Plus one). 
2.	Cut filters in half using ethanol flamed tweezers and scissors. 
3.	Wash the filter with 350 μL of Tissue and Cell Lysis Solution containing the Proteinase K and mix by pipetting up and down several times.
4.	Vortex for 10 seconds. Make sure both halves of the filter are fully submerged in the Tissue and Lysis Solution containing the Proteinase K. 
5.	Incubate at 65 °C for 20-30 minutes on heat block (3X 5 min at 1300 RPM, 1X-3X 5 min at 0 RPM); vortex every 5 minutes for 15 seconds. Make sure the filter is open. 
6.	Place the samples on ice for 3-5 minutes.

**Precipitation of total nucleic acids**

1.	Add 150 μL of MPC Protein Precipitation Reagent to 300 μL of lysed sample and vortex vigorously for 10 seconds. 
2.	Pellet the debris by centrifugation at 4 °C for 10 minutes at 14,000 x g in a microcentrifuge. If the resultant pellet is clear, small or loose, add an additional 25 μL of MPC Protein Precipitation Reagent, mix and pellet the debris again. 
3.	Transfer the supernatant to a clean microcentrifuge tube and discard the pellet. 
4.	Add 500 μL of cold isopropanol to the recovered supernatant. Invert the tube 30-40 times. 
5.	Pellet the total nucleic acids by centrifugation at 4 °C for 10 minutes in a microcentrifuge. 
6.	Turn heat block to 37 °C.
7.	Carefully pour off the cold isopropanol without dislodging the total nucleic acid pellet. 

**Removal of contaminating DNA from total nucleic acids preparation**

1.	Remove all of the residual isopropanol with a pipette. 
2.	Prepare 200 μL of DNase I solution for each sample by diluting 5 μL of RNase-Free DNase I up to 200 μL with 1X DNase Buffer. 
3.	Completely resuspend the total nucleic acid pellet in 200 μL of DNase I solution. 
4.	Incubate at 37 °C for 10 minutes. Note: Additional incubation (up to 30 minutes) may be necessary to remove all contaminating DNA. 
5.	Add 200 μL of 2X T and C Lysis Solution; vortex for 5 seconds. 
6.	Add 200 μL of MPC Protein Precipitation Reagent; vortex 10 seconds; place on ice for 3-5 minutes. 
7.	Pellet the debris by centrifugation at 4 °C for 10 minutes at 14,000 x g in a microcentrifuge. 
8.	Transfer the supernatant containing the RNA into a clean microcentrifuge tube and discard the pellet. 
9.	Add 500 μL of cold isopropanol to the supernatant. Invert the tube 30-40 times. 
10.	Pellet the purified RNA by centrifugation at 4 °C for 10 minutes in a microcentrifuge. 
11.	Carefully pour off the cold isopropanol without dislodging the RNA pellet. 
12.	Rinse twice with 500 μL cold 70% ethanol, being careful to not dislodge the pellet. Centrifuge at 4 °C for 10 minutes at 14,000 x g. Pour out the cold 70% ethanol. Remove all of the residual ethanol with a pipette. 
13.	Let pellet air dry for ~30 min. 
14.	Resuspend the RNA in 35 μL of TE Buffer. Place the tubes for 5 minutes at 50C on a heatblock at 1400 RPM. 
15.	Add 1 μL of RiboGuard RNase Inhibitor (optional). 


# Ribogreen Quantification

**Materials:**

*	Diluted RNA standard (keep in small aliquots and date – use within 1 month)
    +	Make 100 ng/ml: Stock is 100g/ml in fridge, dilute 1l:999l in 1X TE 
    +	Make 10 ug/ml: 1:10 dilution of stock, dilute 1l:9l in 1X TE (optional)
*	1X TE diluted from 20X TE provided in kit
    +	To make 1ml, 50 μl of 20X TE + 950l water
    + To make 2ml, 100 μl of 20X TE + 1900l water
*	Multiply the number of wells you will be using (including the standard curve by 50, to calculate the number of μL needed of 1X TE and Ribogreen (step 3)
*	[Black 96-well plate (Costar)](https://www.fishersci.com/shop/products/96-well-solid-black-white-polystyrene-microplates/07200590)
*	Pull out Ribogreen to thaw in the dark and make up the Ribogreen solution

**Prior to Start:**

1.	At least 1 hour before you are ready to read, turn on the computer and open the software for the plate reader (Software: SoftMaxPro). THEN turn on the plate reader. The software will not find the plate reader unless you follow in this order; click on corner icon (SpectraMax), select instrument to connect. During warm-up of plate reader, follow the protocol listed below.

2.	Plan your plate. You will need one well for each of 7 standards (add the number of l equal to the ng/mL; 50 ng/mL = 50 L) and one well for each sample. You can reduce or add standards if you think your nucleic acid falls outside of the standard range. Do not use the edge rows/columns (plate reader may not be accurate here at all edge wells). 
Also, run duplicates of unfractionated RNA.

3.	Make 1:2000 Ribogreen mixture from aliquot of Ribogreen reagent and 1X TE. E.g. If you need a total of 2 mL of 1:2000 Ribogreen, mix 1 L Ribogreen with 1999 L 1X TE. Protect from light.

**Set up plate:**

1.	Add 1X TE to wells in plate. For all samples, add 48 μL 1X TE. For standards, add 50 μL – x 1X TE (for example, for the 5 ng/mL well, add 45 μL). Use table below if needed. 
    + Use the 1:10 RNA diluted stock (10 ug/ml) for the *2 highest standards in the curve, and then use the 1:1000 (100 ng/ml) for the rest.

<center>

| Well   |   Volume 1X TE (μL)    |   Volume of RNA (μL) | RNA Concentration (ng/μL) |
|:-------------:|:-------------:|:-------------:|:-------------:|
| B2    |   49    |   1*    |   100 |
| C2    |   0    |   50    |   50 |
| D2    |   25    |   25    |   25 |
| E2    |   40    |   10    |   10 |
| F2    |   45    |   5    |   5 |
| G2    |   49    |   1    |   1 |
| B3    |   50    |   0    |   0 |

</center>

*use 1:10 – 10 g/ml	RNA concentration (ng/mL)
Fill rest with nucleic acid	49	1	Determine by standard curve


2.	Add standard or template according to the table above. Consider adding additional positive and negative controls (e.g., additional standards to run as unknown samples or additional blanks).
3.	Finally add 50 μL of 1:2000 Ribogreen to each well, pipetting up and down three times to mix. At this step, you’re completing a 1:100 dilution of your RNA
4.	Adjust settings and fill template editor information:



  *Settings:*

     Read Mode: FL
     Wavelength: 480-520 nm
     Read Type: Well Scan (will take the average of 5 readings in each well)
     Plate type: 96 well standard opaque
     Read Area: highlight and assign standards, blanks, and sample wells (avoid using outer wells)

  *Template Editor:*
     
    Indicate wells containing standards and enter their concentration

    Standard curve will require you to input the concentration but it is in mg/ml, this is OK. Fill in the above values from your standard curve
    Also denote the plate blank
      Indicate wells containing samples – click assign each time you highlight a well.
     
  *Press Read*
 


5.	It will only take a minute or 2 to read your plate. 
    + Standard curve – check your standard curve to make sure ‘BackCalcConc’ is the same as your input ‘Conc’, and that your curve looks correct.
    + One way to calculate your concentrations is to take the ‘Value’ column, which is absorbance, plot this for the slope, and then back calculate the absorbance of your samples.
6.	Export your data
    + Save your file. This will be in .sda format and will allow you to return to this specific run in the future to inspect run parameters
    + To export the data, click on the 96-well plate in the top left corner of the screen and “export.” In the next window, click the experiment you are interested in exporting data for (usually this is just “Exp 1”), and it will save as a .txt format in the same name as your .sda file. 

**Calculations**

1.	Preform a linear regression of the “Values” column versus the known concentrations of RNA in your standards.
2.	Subtract the “blank” value from your unknown RNA values
3.	Calculate the RNA concentration from the linear regression equation using your unknown values subtracted from the blank. 
4.	First, account for the 1:100 dilution you performed to prep your plate by multiplying by 100.
5.	Second, change units (from ng/ml to ng/ μL) by dividing by 1000



# Before you begin

## Calculate RNA input

Using the ribogreen measurements, calculate how many μL of RNA is needed from each sample for a total of 500-750 ng (I use 500 ng). You may need to make 10X, 100X, or 1000X dilutions of your RNA in 1X TE in order to measure them properly. I always do a freeze thaw after my RNA extraction to make sure my RNA is properly hydrated.  

## Refractometer Modification

[This modification comes from the Buckley lab](https://github.com/buckleylab/Buckley_Lab_SIP_project_protocols/blob/master/RNA_SIP/RNA_SIP.md)

**Items needed:**

* Small sharp scissors
* AR200 Digital handheld refractometer (Cat. No. 13950000)
* Electrical tape
* 100 % isopropanol 
* DEPC water
* Kim Wipes

<center>

![Image of refactometer modification. Note: we add 10 μL using the modifcation not 75 μL](/Users/oliviaahern/Pictures/modification.png){width=75%}
</center>




1.	Cut out a circle of electrical tape with a smaller hole inside of it and place inside refractometer and over the edges (look at photo).
2.	If the black electrical tape is too big for the refractometer circle, you will get an error saying that the image is fuzzy. Cut down to appropriate size. 
3.	Make sure the setting is nD-TC
    + Note: this is very important. This measures the density (nD) and compensates for the temperature (TC) so that you have density readings at exactly 20C. You will do your spin at 20C, so you will need to know what the density of your gradients are at the same temperature you spin it at. The lab temperature is not static, so if you don’t have this setting on, your density values will be off by a decent margin and your SIP spins will be incomparable between different days. 
4.	Clean the hole with 10 μL of 100% isopropanol, kim-wipe off the isopropanol. Add 10 μL of DEPC water, kim-wipe off the DEPC water. Add 10 μL of DEPC water. 
5.	Hit calibrate, wait for the instrument to calibrate, then hit read. It should read exactly 1.3330. If it does not, kim-wipe the water and repeat step 4 again. It is important that the refractometer is calibrated consistently between SIP runs. 
6.	If you want to remove the electrical tape, then just pull it off and clean the refractometer with 100% isopropanol and MilliQ water. 



## Make Gradient Salt Solution

Recipe from [Dunford and Neufeld, 2010](https://www.ncbi.nlm.nih.gov/pubmed/20729803)

Combine 

* 50 ml of 1 M Tris-HCl
* 1 ml of 0.5 M EDTA
* to 400 ml of water. 
* Dissolve 3.75 g KCl, then add ddH2O to 500 ml. 
* Filter-sterilize and autoclave. 

The final solution is 0.1 M Tris, 0.1 M KCl and 1 mM EDTA.


## Hydrate your CsTFA

The day before you setup a spin, hydrate your 50 g powdered CsTFA with 13 mL of GSS. Shake vigorously and allow to come to room temperature for several hours to overnight (I do overnight). Measure the RI of the GSS you hydrate the CsTFA with (after the calibration). GSS can increase in density due to evaporation over time. 

*Note:* CsTFA is extremely hydroscopic (i.e. loves water) and will become crusty if you leave the powder out after opening the bottle (i.e. absorbs water through humidity). This step ensures consistency between SIP spins over time. 


# Gradient Setup

Protocol is a derivation of the [Huber lab protocol](https://www.protocols.io/view/rna-extraction-protocol-from-rna-sip-experiments-3byl438ogo5d/v2), [Lueders 2010](https://www.infona.pl/resource/bwmeta1.element.springer-93db329b-6ce7-34d7-a19c-96cac2da3334), [Buckley Lab RNA SIP Protocol](https://github.com/buckleylab/Buckley_Lab_SIP_project_protocols/blob/master/RNA_SIP/RNA_SIP.md), and [Roey Angel's protocol](https://www.protocols.io/view/rna-stable-isotope-probing-bpwympfw.html)


**Protocol** 

1.	Rinse Beckman tubes with 500 μL of 70 % molecular grade ethanol. Hang upside to dry and tap every so often to get out the excess ethanol. 
2.	Label 15 ml tubes with sample names. Do not run more than 6 - 8 samples. You may want to include one No RNA control at first. 
3.	Set your refractometer to nD-TC and do the isopropanol/water/water/1.3330 calibration described above. Do not move forward until the refractometer is calibrated to 1.3330. 
 * nD-TC allows you to read the refractive index at 20C, which is what you run the ultracentrifuge at. Densities will change with temperature, so the density at room temp (~23C) will be different than 20C. Calibrate the refractometer with 75 μL of DEPC water. It should read 1.3330 +/- 0.0002. If it is off, clean the refractometer with 100 μL of 100% isopropanol and read it again.
4.	For 6 samples - Add 30 mL GSS+CsTFA to a 50 mL tube. Measure the RI and bring the solution to 1.3765 with GSS (usually about 3 mL). 
5.	Filter sterilize 5.1 mL into 15 mL tubes and add 185 μL of formamide. Record the RI for each of the tubes after adding formamide (important for Lueders 2010 correction factor). 
6.	Add up to 1 mL minus volume of 750 ng of RNA of the Gradient Salt Solution. E.g. If you are going to add 20 μL of RNA, then add 980 μL of Gradient Salt Solution. Recipe for solution can be found in *Neufeld et al. 2010, JoVe* article. 
 * I usually start with 500 μL GSS minus the volume of RNA and then adjust the density with more GSS (too high) or CsTFA solution (too low) in 50 μL increments. 
7.	Add 750 ng of RNA. Can add 500 - 750 ng, but try not to go lower.
8.	Mix gently by inverting. DO NOT vortex.
9.	Using 10 μL from each tube, measure Refractive Index (RI) on the refractometer. Each tube should measure 1.3729±0.0002. This may be adjusted to optimize peak fractions if needed.
 * If RI is too high or too low, adjust using CsTFA buffer (if too low) or Gradient Salt solution (too high). Add 50 - 100 μL to adjust, then mix and re-measure. DO NOT proceed until each tube is within range.
 * Also, measure pure CsTFA each time to check if there are changes in density (not usually needed).
10.	Fill each 5.1 mL Beckman centrifuge tube using a pipette. Fill to the bottom of the neck. Do not overfill! Place black caps on top. You should notice the bottom half of the black cap is wet. It is too full if fluid is higher or is coming out of the tube. Level is too low if the fluid does not touch the cap.
11.	Determine the mass of each filled tube on the scale by placing each tube in the brown flask stopper with the hole in it and measuring its weight. Make sure the scale’s bubble is in the center before weighing. Each tube should have a partner with comparable mass (within 0.01 g). If one tube is greater than 0.01 g heavier than the other, add GSS in 10 μL increments until the masses are the same.
12.	After looking up the proper configuration for the number of tubes you have (below), pair up tubes with similar masses and load into the rotor. MAKE SURE IT IS BALANCED. Place weighted gold caps on top of tubes (skinny side up; press all the way down), then thread in the caps, white o-ring down. Use a ratchet/torque wrench to tighten to ~ 40 lb.
13.	Place the rotor in the ultracentrifuge in Harriet's Lab. Make sure to only set the rotor down in the base to avoid scratching the code on the bottom. Run @37,000 rpm, 20 °C, for 65 hours. Make sure the program has NO BRAKE (setting 10) for deceleration option.
14.	After setting up your spin, calculate the total volume of the tube (i.e. 5.1 mL + .850 mL) and the amount of formamide use. Multiply those volumes by 0.1 and make a GSS + formamide solution in a 1.5 mL tube from those calculated values. Measure the RI (after calibrating) and subtract that value from 1.3333 for the [Buckley lab correction factor](https://github.com/buckleylab/Buckley_Lab_SIP_project_protocols/blob/master/RNA_SIP/RNA_SIP.md).

**Note:** when the cycle is finished, it will not say “end” or “complete;” it will look like you didn’t start it at all. This is why it is important to check on the ultracentrifuge every day that it is running, to make sure it is still running correctly.

<center>

![Optimal arrangement of tubes in rotor VTi 65.2](/Users/oliviaahern/Documents/GitHub/RNA_SIP/pics/Picture1.png){width=50%}

</center>

# Fractionation 

**Items needed**

* [Eppendorf 500 μL Deep Well Plates](https://www.sigmaaldrich.com/US/en/product/sigma/ep951031801)
* [Eppendorf 500 μL Deep Well Plates Sealing Mat](https://www.sigmaaldrich.com/US/en/product/sigma/ep0030127978)

**Protocol**

1.	Prepare 50 mL tubes of a) 70 % ethanol and b) 100% isopropanol, then place in the -20 freezer for later.
2.	Make ~50 mL of colored MilliQ water with Resazurin dye (add 100 μL).
3.	Rinse low-flow tubing with MilliQ water and 70% EtOH before use.
4.	Set up a ring stand with a test-tube clamp to hold the Beckman tubes.
5.	Sterilize deep well plates and sealing mat before use. Label both the plate and sealing mat with cryolabels. 
6.	Take the rotor out of the ultracentrifuge, place it in the base, bring it to your bench, unload tubes, and place them in the black tube rack.
7.	Set the pump to 0.45 mL/minute. 
8.	Prime tubing with colored MilliQ water.
9.	Screw needle on end of tubing and prime again.
10.	Place a 5 mL Beckman tube gently in the clamp (do not squeeze the tube) and ready the plates. Make sure A1 is the FIRST well filled - this is the heaviest fraction.
11.	Puncture the bottom of the 5 mL tube with a needle. Place a piece of tape over the hole, so that none of the liquid spills out when you make the next hole in Step 13. 
12.	Place the plate under the tube rack. 
13.	Puncture the top of the 5 mL tube with the primed needle that is now attached to the tubing.
14.	Set a stop watch on your phone. Simultaneously press start on the timer and the pump.
15.	Shift rack every 30s to collect a new fraction. Record where each fraction is on the sheet. Look at the template below for an example of how to set up a plate.
16.	After 11 minutes, you have collected all 22 fractions. Turn off the pump. 
17.	Now cut a piece of sterile sealing film (like BioRad Sealing Film B) into thirds. Cover the fractions you just collected with the third piece of sealing film. 
18.	Collect the second set of fractions on the other side of the place (i.e. RNA2 from the template) starting with well H12.
19.	Once you have finished one plate, remove the sealing film and cover with the sealing mat, careful to match up the A1 on the sealing mat and the plate. 
20.	Measure and record the RI for each fraction.
21.	Make sure the setting is at nD-TC and repeat the isopropanol/water/water/calibrate/1.3330 every time before you start reading a set of fractions. Do not proceed if the DEPC water is not at 1.3330. Start with the lightest fraction first (i.e. 22) to prevent residual denser fractions from interfering with your readings. 
22.	Add 10 μL of DEPC water or sample. The middle fractions (~11-13) should be ~1.3729, or approximately the same density as the starting solution. If this is not the case, the samples may need to be re-run.
23.	Repeat fractionation for each sample. Repeat the isopropanol/water/water/calibrate/1.3330 step before each set of fractions.
24.	Add 1X volume ice cold 100% isopropanol to each well. Invert gently 30 times and place in the -20 °C overnight. 
25.	Clean tubing by flushing with MilliQ and then 70% Ethanol. Let the ethanol drain out and dry by hanging the tubing from the center over a paper towel.




<center>

![Example Plate](/Users/oliviaahern/Documents/GitHub/RNA_SIP/pics/Picture4.png){width=100%}



![Left. Fractionating into 96-well plates. Right. After fractionating, make sure all of your fractions are level (contain the same amount of CsTFA+RNA).](/Users/oliviaahern/Documents/GitHub/RNA_SIP/pics/Picture3.png){width=70%}

</center>

# RNA Precipitation

Before precipitating – if you have an odd number of plates – make a “buddy” plate for the isopropanol and ethanol washes using water. Make sure that it weighs about the same as the plate with CsTFA.
*Note:* CsTFA is heavier than water, so you may need to add like 1.1-1.3X more water to each well to compensate for differences in density. 


1.	Spin the plates in the centrifuge at 4 °C, 4250 rpm for 45 minutes. 
2.	Take off the lids (remember to label the lids) and very quickly dump the isopropanol wash into the trash can. While the plate is still upside down, place a paper towel over it to remove the residual isopropanol. 
3.	Flip the plate back over. Add 150 μL of ice cold 70% ethanol to each well. 
4.	Spin at 4 °C, 4250 rpm for 25 minutes. 
5.	Take off the labelled lids and very quickly dump the ethanol into the trash can. While the plate is still upside down, place a paper towel over the wells to remove the residual ethanol.
6.	Dry the RNA by letting the plate sit out for ~30 minutes. 
7.	Hydrate the RNA by adding 20 μL of 1X TE. Vortex and spin down at 4250 rpm for one minute.
8.	A freeze-thaw always works best for me before ribogreening. Let the plates sit in the -80 °C overnight before ribogreening.  

# Quantification/Correction Factors 

## Quantifying

Ribogreen all fractions to determine concentrations.
Using the protocol described on p. 4-5 but with 2 μL template and modified plate setup to allow easier quanitifcation from 96 well plates. 

<center>
![Example ribogreen plate for RNA-SIP fractions from 96 well plates. Std = standard.](/Users/oliviaahern/Documents/GitHub/RNA_SIP/pics/Picture2.png){width=50%}

</center>


We use correction factors to compensate for differences in the GSS and formamide between runs. This was not done previously with the liquid CsTFA solution. There are two ways to correct currently. The first is from Lueder’s, which is not a published protocol. The second is from the Buckley lab. At this point and time (Sept 2022) there has been no recent research published on correction factors for RNA SIP (except Buckley’s). 

## Leuders

Use CsTFA standard curve from figure 2B (below) Lueders 2010 to convert RIs into buoyant density and apply the correction factor.


<center>

![Relationship between RI and Buoyant Density from Leuders](/Users/oliviaahern/Documents/GitHub/RNA_SIP/pics/Picture5.png){width=50%}

</center>


*Correction factor:* 

    (density of CsTFA + Gradient Buffer + formamide: 1.98) - density of CsTFA solution in water adjusted to RI of bought solution. 
    
Therefore, if the RI of your CsTFA + Gradient Buffer + formamide was 1.3783, then the buoyant density of is 1.91549008. Your correction factor would be 0.06450992 (1.98-1.91549008). The formula in excel is:             1893.982*POWER(RI_CsTFA+GSS+Form,2)+5230.8018*( RI_CsTFA+GSS+Form)-3609.6804). 


## Buckley 

This is derived from the [Buckley Lab SIP Protocol](https://github.com/buckleylab/Buckley_Lab_SIP_project_protocols/blob/master/RNA_SIP/RNA_SIP.md)

We calculated the correction factor in step 13 of Gradient Setup. Subtract that value (i.e 0.0051) from all of your RI values from your SIP spin and then calculate using the equation in the link:


    RI corrected = RI observed – (RI Buffer - 1.3333)
    RI observed = Either the GSS + CsTFA or fractions
    RI Buffer = GSS + Formamide (no CSTFA)
    Buoyant Density = 163.559 – 262.271*(RI corrected) + 105.281*(RI corrected)^2

## Correcting for differences in lot numbers

[ThermoFisher/Fisher Scientific](https://www.fishersci.com/shop/products/cesium-trifluoroacetate-thermo-scientific/AA4463309) sources their CsTFA from [Alfa Aesar](https://www.thermofisher.com/order/catalog/product/044633.18). Alfa Aesar sources it from a third party. During the year that it took me to spin 84 RNA-SIP samples, Alfa Aesar ran out of the lot I was originally using [lot #X28H038](https://www.thermofisher.com/document-connect/document-connect.html?url=https://assets.thermofisher.com/TFS-Assets%2FCCG%2FAlfa-Aesar%2Fcertificate%2FCertificates-of-Analysis%2F044633-X28H038.pdf) and it was replaced by [lot #T12J009](https://www.thermofisher.com/document-connect/document-connect.html?url=https://assets.thermofisher.com/TFS-Assets%2FCCG%2FAlfa-Aesar%2Fcertificate%2FCertificates-of-Analysis%2F044633-T12J009.pdf). The two different lots had two different purities from their Certificate of Analysis, X28H038 was 99.1% pure and T12J009 was 99.9% pure. When the same sample was run twice, the purer T12J009 had 12C peaks that were ~1.3727 while the less pure X28H038 had denser 12C peaks of ~1.3731. I measured the RI of the two different lots (measured the RI after hydrating overnight with 13 mL GSS) and found that there was a difference of RI 0.0004. Therefore, we could correct for differences between lots. 

Remember to take down the lot # of the CsTFA you have and check the purity from the COA. 

You should also note that it took ~5-6 months for them to restock the CsTFA. They tend to make a giant batch, bottle it all up, sell it all, then wait and make new stuff. So, if you can, buy all of your CsTFA you need for the entire project at once. 


# KAPA SYBR Fast One-Step RT-qPCR 

Follow using the manufacturer's instructions with 10 μL reactions and 1 μL of RNA for input. 

**Master Mix**

| Reagent   |   Initial Conc.   |   Final Conc. | Volume 1 rxn (μL) | Volume 96+6 rxns (μL) |
|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| SYBR 2X buffer | 2X | 1X | 5 | 540 |
| dH2O | - |	-	| 3 |	324 |
| 805R Primer	| 10 μM	| 0.4 μM | 0.4 | 43.2 |
| 341F Primer	| 10 μM	| 0.2 μM	| 0.2	| 21.6 |
| 50X Rox High	| 50X	| 1X	| 0.2	| 21.6 |
| RT Mix	| 50X	| 1X	| 0.2	| 21.6 |
| Template	| - |	-	| 1 |	108 |



# Check out your curves

First, normalize your RNA concentrations to the SIP fraction with the highest concentration (Ratio of Maximum Quantity). Graph your 12C control and 13C-labelled SIP fractions with corrected Buoyant Density on the x-axis and normalized Ratio of Maximum Quantity on the y-axis. 


```r
library(ggplot2)
library(tidyverse)

qpcr=read.csv(file='/Users/oliviaahern/Documents/R/Exp4/25Aug22/qpcr_6Oct22.csv',
              header=T)
# dim(qpcr)
qpcr_sub=subset(qpcr, Buckley > 1.74)

make_bar_relabun <- function(df, selection){
  df_out <- df %>% 
    filter(MC %in% c("MC1",selection))
  ggplot(df_out, aes(x = Buckley, y = qPCR_RMAX)) +
    scale_fill_manual(values=colls) +
    scale_colour_manual(values=colls) +
    facet_grid(~TP, scale='free_x', space="free", shrink=TRUE) +
    geom_point(aes(colour=MC, 
                   fill = MC), size=1.3) + 
    geom_line(aes(colour=MC)) + 
    labs(x="Buoyant Density (g/mL)", y = "Ratio of Maximum Quantity") +
    theme_bw() +  scale_x_continuous(limits = c(1.76, 1.83)) +
    theme(axis.text = element_text(color ='black',size=6, hjust=1,vjust=1),
          axis.text.x=element_text(size=6, angle=90),
          axis.title = element_text(color='black',face='bold',size=8),
          legend.position = "none",
          panel.grid=element_blank(),
          legend.text = element_text(size=8),
          legend.key.size = unit(0.25,'cm'),
          strip.text.x = element_text(
            size = 10, color = "black", face = "bold"),
          strip.background = element_rect(
            color="gray80", fill="gray97", size=1, linetype="solid"),
          panel.spacing = unit(0.05, "lines")
    )
}

colls=c('gray50',"#a44f9a")
m2=make_bar_relabun(qpcr_sub, "MC2") + geom_text(data = data.frame(x = 1.81, y = 1, TP=1.5, label = "MC1 12 Control"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="gray50",fontface='bold') + geom_text(data = data.frame(x = 1.81, y = .90, TP=1.5, label = "MC2 13C-Methanol"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="#a44f9a", fontface='bold')
colls=c('gray50',"#6870c8")
m3=make_bar_relabun(qpcr_sub, "MC3")+ geom_text(data = data.frame(x = 1.81, y = 1, TP=1.5, label = "MC1 12 Control"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="gray50",fontface='bold') + geom_text(data = data.frame(x = 1.81, y = .90, TP=1.5, label = "MC3 13C-Ethanol"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="#6870c8", fontface='bold')
colls=c('gray50',"#56ae6c")
m4=make_bar_relabun(qpcr_sub, "MC4") + geom_text(data = data.frame(x = 1.81, y = 1, TP=1.5, label = "MC1 12 Control"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="gray50",fontface='bold') + geom_text(data = data.frame(x = 1.81, y = .90, TP=1.5, label = "MC4 13C-Acetate"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="#56ae6c", fontface='bold')
colls=c('gray50',"#af953c")
m5=make_bar_relabun(qpcr_sub, "MC5") + geom_text(data = data.frame(x = 1.81, y = 1, TP=1.5, label = "MC1 12 Control"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="gray50",fontface='bold') + geom_text(data = data.frame(x = 1.81, y = .90, TP=1.5, label = "MC5 13C-Glucose"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="#af953c", fontface='bold')
colls=c('gray50',"#ba4a4f")
m6=make_bar_relabun(qpcr_sub, "MC6") + geom_text(data = data.frame(x = 1.81, y = 1, TP=1.5, label = "MC1 12 Control"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="gray50",fontface='bold') + geom_text(data = data.frame(x = 1.81, y = .90, TP=1.5, label = "MC6 13C-Xylose"), 
                   aes(x = x, y = y, label = label), size = 3,
                   colour="#ba4a4f", fontface='bold')
library(cowplot)
plot_grid(m2,m3,m4,m5,m6,aligh='hv',ncol=1)
```

![](/Users/oliviaahern/Documents/GitHub/RNA_SIP_Protocol/docs/index_files/figure-html/qpcr_a-1.png)<!-- -->

Above are buoyant density curves over time from a batch experiment using 20% 13C-labelled substrates vs. the control. Note how different substrates show different buoyant density curves over time. 

Determine how many RNA SIP fractions you want to send for 16S and 18S amplicon sequencing and then proceed to the next step. 

# cDNA First Strand Synthesis

This protocol is from [Biorad's iScript Select cDNA synthesis ](https://www.bio-rad.com/webroot/web/pdf/lsr/literature/10001023B.pdf)

This is for 20 μL reactions. But you can use 10 μL reactions if just using the cDNA product for one amplicon PCR. 

**Protocol 12 μL Reactions**

In PCR hood (after waiting for the UV light to go off and wiping down with 10% bleach, 70% ethanol, and RNASeZap), make up master mix using the volumes below in the low input tubes on ice. Dispense 4.2 μL into each 200 μL PCR tube tube over ice. Spin down the samples on a microcentrifuge so that the mix is on the bottom of the tube. Add nuclease-free water (from kit) to each tube in the pre-calculated values. 

Component   |   Vol/Rxn   |   Vol/35 Rxns
------------- | -------------   | -------------
5x iScript Reaction Mix   |   2.4   |   84
iScript Reverse Transcriptase   |   1.2   |   42
Random Primers    |   0.6   |   21
Nuclease-free water   |   Variable   |   Variable
RNA template (100 fg - 1 ug total)   |   Variable   |   Variable

For a 12 μL, the total volume for the master mix in each tube should be 4.2 μL and the volume of the RNA + water should be 7.8 μL. 

RNA Input for each reaction:

* Community samples are 12 μL reactions and input of 25 ng
* Fractions are 12 μL reactions, input of either: 
    + 100 pg 
    + 500 pg
    + 1.5 ng
  

Place into thermocycler and run program under Olivia A > iScript cDNA 1708897. 

  **Thermocylcer Program**

    Priming  5 min at 25°C
    Reverse Transcription  30 min at 42°C
    RT inactivation  5 min at 85°C
    Optional Hold at 4°C

# 16S PCR 

To make sure that the cDNA synthesis worked, we run a quick 16S PCR with the [taq](https://www.neb.com/products/m0531-phusion-high-fidelity-pcr-master-mix-with-hf-buffer#Protocols,%20Manuals%20&%20Usage) and [515F/926R](https://ami-journals.onlinelibrary.wiley.com/doi/full/10.1111/1462-2920.13023) primers from the [sequencing center](https://imr.bio/protocols.html). We are just going to run a subset of our samples (out of the 14 96-well plates for sequencing, we will PCR maybe 4-8 samples per plate).


Component   |   Conc   |   10 uL Rxn
------------- | -------------   | -------------
Water   |   X   |   6.30
HF PCR Buffer   |   5X   |   2
dNTPS    |   10 mM   |   0.2
F Primer 515Y   |   10 uM   |   0.2
R Primer 926R   |   10 uM   |   0.2
Phusion Taq   |   2 U/uL  |   0.1
Template | X | 1



  **Thermocylcer Program**

    1 min at 98°C
    
    25 cycles of: 
    30 sec at 98°C
    30 sec at 55°C
    60 sec at 72°C
    
    9 min at 72°C
    Optional Hold at 4°C
    

Verify the bands using a 1% agarose gel. 

# Send for Sequencing

We are sending our cDNA libraries to [IMR](https://imr.bio/protocols.html) for 16S and 18S sequencing.

# Items used in protocol

<center> 

Item Description  | Cat. No.
------------- | -------------
KAPA SYBR FAST One Step qRT-PCR Universal 1,000 20 uL rxns | KK4652
MasterPure™ Complete DNA and RNA Purification Kit | MC85200
Eppendorf 500 μL 96 deep well plates | 9510131801
Eppendorf 96 deep well plate sealing mat | 0030127978 
Millipore Express 0.2 μM Filters 25 mm | GPWP02500	
Cesium Triflouroacetate 50g | AA4463318
iScript Select cDNA Synthesis Kit | 1708897
BioRad “B” PCR Plate Sealing Film | MSB1001
BD Precision Glide Needles, 23 gauge | 14-826A
USA Scientific PCR Cooler Tube Rack | 4051-0509
Corning Sterile Reagent Reservoirs | 4870
GoTaq DNA Polymerase | M3008
ThermoScientific Tris-HCL, 1M Solution pH 8.0, Ultrapure/molecular grade | J22638-AE
Invitrogen 0.5 M EDTA pH 8.0 | AM9260G
DEPC-Treated Water | AM9906
Beckman optiseal polypropylene centrifuge tubes, 4.9 mL | 362185
ThermoScientific Potassium Chloride, 99% Molecular Grade | J64189.36
Fisher Tris-EDTA (10X Solution), pH 7.4 | BP2477-100 
Axygen 1.7mL low retention microcentrifuge tubes | MCT-175-C-S
Axygen 0.2ul low retention, Maximum Recovery, PCR tubes | PCR-02-L-C
BioRad Multiplate PCR Plates, 96-well clear | MLL9601
Costar 96-well Black Flat bottom Polystrene, 25 per pack | 3915


</center>

Sourced isotopes from Cambridge Isotope Laboratories. Sourced primers from New England Biolabs (100 μM, hydrated). 




