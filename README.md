# Nano Design Days (1B)

### Project repository for group 14’s 1B nano design days. A short, end-of-term project combining course material learned over 1B nano eng.

This project explores the use of nanotechnology (gold nanoparticles) for blood glucose detection.

### Chemistry Documentation:
<br />
<img src="https://github.com/Ala-Kazam1234/NanoDesignDays1B/blob/main/ChemDocumentation.png" width="650" height="400">

The main idea is that the colour outcome of the nanoparticles after the reaction occurs *directly* relates to the amount of initial glucose concentration. 

The reaction was designed to occur on a non-traditional lateral flow assay (LFA). This lets us see a coloured stain of nanoparticles to be imaged. 

See [here](https://github.com/Ala-Kazam1234/NanoDesignDays1B/blob/main/LFA/lfa%20design.jpg) for LFA design.
<br />
See [here](https://github.com/Ala-Kazam1234/NanoDesignDays1B/blob/main/LFA/LFAs%20-%20After.png) for the post-reaction colours. 

---
### SolidWorks 

In order to image the LFAs, an imaging box was designed. It's job is to minimize external light, provide steady internal light, and hold the LFA in place. The imaging box was designed in SolidWorks, and 3d printed to fit snug around our camera (the Orbecc Astra Camera). 

See [here](https://github.com/Ala-Kazam1234/NanoDesignDays1B/blob/main/Setup/Imaging%20box%20design.jpg) for the drafts/sketches.
<br />
See [here](https://github.com/Ala-Kazam1234/NanoDesignDays1B/tree/main/SolidWorks) for the SolidWorks Designs - they come as part files. 
<br />
See [here](https://github.com/Ala-Kazam1234/NanoDesignDays1B/tree/main/SolidWorks/images) for the images. 
<br />
This is what our final set up looked like:
<br />
<img src="https://github.com/Ala-Kazam1234/NanoDesignDays1B/blob/main/Setup/setup%20-%20team%2014.jpg" width="650" height="400">

---
### MATLAB 

After the images had been taken, MATLAB was used analyze an image with an unknown concentration of glucose and output a known concentration based on a match with one of the calibration images obtained from previous LFA imaging with known concentrations. 

Design Parameters:
1. Access the unknown image from local files.
2. Analyze the colour of the unknown image and compare it to each of the calibrated images.
3. Determine which of the calibrated images the unknown image is most similar in colour to.
4. Output one of the following options:
    - A range of possible glucose concentrations for the unknown sample.
    - A percentage indicating similarity between the unknown sample and one of the calibrated samples.
    - A concentration taken from the closest calibrated image.

5. Output whether the sample indicates a normal blood glucose level, prediabetes, or diabetes.


---
Refrences: 

1.  University of Waterloo, 2021,“Chemistry Documentation”, Ideas Clinic Design Days NE102, lecture notes.
1.  University of Waterloo, 2021, “Design Components”, Ideas Clinic Design Days NE102, lecture notes.
