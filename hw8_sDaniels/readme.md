BAD PLOT:

This plot is from “How does the presence of bar affects the fueling of supermassive black holes ? An IllustrisTNG100 perspective”, ArXiv Preprint 2 November 2023. This plot has two main issues: 
-ambiguity: there is no way to know how densely the points are plotted in the regions where the points overlap. Setting an alpha value to create translucency would allow us to see variation within the dense region.
-incorrectness: the figure caption does not correspond to the figure (the rest of the figures were red and black histograms, so they must have just copied and pasted that part for every caption). 

￼<img width="582" alt="Screenshot 2023-11-28 at 4 54 05 PM" src="https://github.com/SHDaniels/DSPS_sDaniels/assets/87045537/45904813-0fde-407a-bfa1-3e7667f827ed">


GOOD PLOT:

This figure is from “SuperCAM CO(3 − 2) APEX survey at 6 pc resolution in the Small Magellanic Clouds”, Submitted to the ArXiv on 31 Oct 2023. It is a map, showing locations where this telescope took observations. I like the presence of gridlines for the RA and Dec, because otherwise we would incorrectly assume that they would be straight. The locations of the observations are clear from the white contours, and the yellow contours clearly mark the previously-observed areas. I like that it is superimposed on an image so that we can see where the matter is and get a sense of why they looked at this region. I wish that there were a colorbar for the 24 micrometer part of the image, just because the reader doesn’t necessarily know that the color scale indicates. However, it is not the main point of this graphic, so I’m still calling it a good graphic even though it is missing that information. 
￼<img width="467" alt="Screenshot 2023-11-28 at 4 53 56 PM" src="https://github.com/SHDaniels/DSPS_sDaniels/assets/87045537/bc24e945-edee-4bb2-a619-435a5f8242b4">

Part 2: Improved research plot

This is a plot that I made to show the size distribution of implanted objects that were retrieved and that were not retrieved by my convolutional neural network.

<img width="754" alt="Screenshot 2023-11-28 at 3 30 09 PM" src="https://github.com/SHDaniels/DSPS_sDaniels/assets/87045537/a9ad07ac-a6c0-41dc-9b87-ea29897ebcd1">

Above is the initial plot. Below is the improvement.
![Screenshot 2023-11-28 at 3 45 44 PM](https://github.com/SHDaniels/DSPS_sDaniels/assets/87045537/ed7e9d42-0e69-47b8-a672-f6f8a802fba7)



Figure 4: Neural network classification outcomes on different implanted transient intensities. This histogram shows the results of a classification algorithm that was meant to identify implanted transients. The transients have a variety of intensities, specifically multiplicative intensities, which are plotted on the x axis. The y axis shows how often each of these intensities occurs. Three quantities are plotted: the implantations that the classification algorithm missed, the implantations that the algorithm correctly detected, and the sum (all implanted transients). The correct detections make up a larger percentage of the total implantations as the intensity increases.

While the initial plot contains all the same information as the final plot, it is harder to decipher. The colors in the legend do not correspond to the colors on the histogram because the transparent layers are stacked in the wrong order. I fixed this in the second version, as well as adjusting the labels to be more clear ("non-detected" is less ambiguous than "missing", since it is not clear what was missing). Finally, I changed the x axis so that the number corresponding to the histogram bin is centered on each bin, so that it is clear what each stack corresponds to.

