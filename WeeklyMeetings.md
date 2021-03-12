# Meeting of 3/12/2021
Updates: KI printing with NaBr; alternative bromium/indigo dyes found; CAD malignancy scales with lesion density

## 1. Phantom printing
a.	Epson printer: Print with KI successful, but streaky. Many head cleanings have not fixed it. Initializing new printer <br>
b.  Will insert spiculated mass #9 into NaBr hetero dense phantom and vary print params: <br>
        - Sizes 6, 7, 8 mm <br>
        - Ink density 100%, 90%, 80% <br>
c.	Roland printer: Tyrion purple causes sediment. Explore additional pigment dyes for DEG diethyl ether inks <br>

## 2. Virtual Lesion pipeline
a.	Mass classes: spiculated and lobular @ 1.56, 1.26, 1.06 mg/cc density <br>
b.    Server downtime caused delays. Getting MC-GPU results for 4 new lob masses @ 1.26 mg/cc, Spiculated masses 9, 10 @ 1.26 mg/cc
c.	High separation between spiculated and lobular classes. Will serve as baseline and justification for mass selection for printing <br>

## 3. Observer Study
a.  Additional metalic stickers ordered, checked in on PurchD status <br>
b.  Independently ordered 3M tape sheets, arrived. Will use next time in lab

### To Do:
1.  <br>
2.  <br>


# Week of 3/03/2021
Updates: KI test swatches x-rayed again, shows consistent signal; Tyrian purple shows signal; CAD shows high malignancy score for spiculated masses

## 1. Phantom printing
a.	Epson printer: Print with KI - successful with grayscale and RGB; Check that the I0 is not changing from shot to shot. Should be the same<br>
b.	Roland printer: Use Tyrion purple - mixed with yellow eco-sol ink

## 2. Virtual Lesion pipeline
a.	Mass classes: spiculated and lobular <br>
b.	Visualize/display images of masses in phantom <br>

## 3. Observer Study
a.  Large and small MC clusters: 10 mm and 20 mm, roughly same density so number of visible specks is the same. <br>
b.  MC Pilot study with classf'n task. Might have to make additional templates as we see tradeoff between maintaining number of specks vs density of specks. <br>
c.  To increase difficulty, maybe add PMMA on top of phantom to increase noise, decrease contrast. <br>
d.  If fewer than ~5 specks in cluster, may be ignored. Important to distinguish number of specks in cluster then <br>

### To Do:
1b. If tyrian purple not soluble, consider using regular ink in Roland Printer <br>
2a. Look at lobular results, using same density of 1.56 Compare difference in average CAD scores. For pilot study, use default density of 1.06, to make it difficult <br>


# Week of 2/22/2021
Updates: KI test swatches printed; tyrian purple and ink ordered, new MC templates made with fixed speck density, equal ROI spacing of 35 mm

## 1. Admin
a.	GitHub for agenda, images, phantoms <br>
b.	Project timeline, replacement <br>

## 2. Phantom printing
a.	Epson printer: Print with KI - results in progress <br>
b.	Roland printer: Use Tyrion purple - ordered <br>

## 3. Virtual Lesion pipeline
a.	Mass classes: spiculated and lobular <br>
b.	Worked with Kenny on fixing bounding box size; numerous issues <br>

## 4. Observer Study
a.  Large and small MC clusters: 10 mm and 20 mm, same # calcs so density different. <br>
b.  Pilot study with 2 tasks: detection and classfn. 2AFC observer picks which is smaller/larger, start w FFDM. <br>

### To Do:
2. a. Check that the I0 is not changing from shot to shot. Should be the same <br>
3. a. Use scientific computer to access virutal models from g-drive, onto network <br>
3. b. Need to visualize/display images of masses in phantom <br>
3. c. See if CAD gives higher scores for spiculated, could serve as evidence for features we took. Even if CAD doesn't distinguish, can do observer study form bases for classf'n task <br>


# Week of 2/03/2021
Updates: github repositories made for projects, data, meeting notes

## 1.	Admin
  a.	GitHub for agenda, images, phantoms <br>
  b.	Project timeline, replacement <br>

## 2.	Phantom printing
  a.	Epson printer: Print with KI <br>
  b.	Roland printer: Use Tyrion purple <br>
  c.	Buy empty refillable cartridge <br>

## 3.	Virtual Lesion pipeline
  a.	Questions on robustness of CAD program - VICTRE project <br>
  b.	Mass detection/score varies with background <br>
  c.	Worked with Kenny on fixing bounding box size; numerous issues <br>
