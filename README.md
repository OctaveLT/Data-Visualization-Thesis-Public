# Visualizing patient health data to determine treatment strategy effectiveness and improvements

This repository contains the results from my Master Thesis at [KTH](www.kth.se). Please note that the patients' data used for the picture below are owned by [Evira](www.evira.se) and thus not given in this project. For more information about it, please contact me at ole_tullier@orange.fr. 

Find the entire report via this link: [Coming](todo).

![Overall interface of the visualization](/finalProduct.PNG)

The project has been enabled and supported by [Evira](www.evira.se).

## Abstract

Pediatric obesity is a disease complex to analyze and hard to treat. Therefore, helping and supporting clinicians in curing children is needed. This thesis investigates the value of a clinical  decision support tool to address this issue. The study was carried in Evira company by following the user-centered design thinking method. The user research, carried out with semi-structured
interviews at Martina Barnsjukhuset and Capio Vårdcentral Zinkensdamm, provided the users needs. Later, after sketching and brainstorming around those requirements, a prototype was imagined and created. Next, this prototype was tested by experts during task-based and semi-structured interviews. This evaluation phase concluded that the prototype was intuitive and effective. A final prototype corrected some of the requests obtained during the evaluation. Further research can still be carried out in order to fine-tune this last prototype.
> Find the entire report at [Coming](todo).

## Interactions with the interface

### Change of duration

By using the button in the right-top corner, you have the choice between four period of time (1 month, 3 months, 1 year, 3 years) that will re-update the three top charts accordingly.

<img alt="Zoom and pan in the parallel chart" src="/gifs/durationChange.gif" height="250"/>

### Parallel graph interaction - Zooming & Panning 

You can easily interact with the parallel graph in the right-top corner. You can zoom in or out and pan the scales. In addition to that, you can freeze the current treatment year chosen by clicking. The lines are highlighted or greyed if you hover them or not! 

<img alt="Zoom and pan in the parallel chart" src="/gifs/parallelGraphInteractions.gif" height="250"/>

### Patients Activity hover highlighting

Two lines can be compared in each line graph. The green one corresponds to the current year and the one greyed to the last year. Hovering on them will make them hightlighted and greyed for a better visualization.

<img alt="Gif of Patients Activity hover highlighting interaction of line charts" src="/gifs/patientsActivity.gif" height="250"/>

### Tooltips

All the views come with a tooltip to give details on demand and more additional information about the data hovered such as the median, the current data, ...

<div style={{
      display: flex;
      justify-content: space-around;
     }}>
  <img alt="Tooltip in duration between visits view" src="/gifs/durationVisits.gif" height="250"/>
  <img alt="Tooltip the right-bottom corner component" src="/gifs/lastHovers.gif" height="250"/>
  <img alt="Tooltip in the sankey chart" src="/gifs/sankeyChartsHover.gif" height="250"/>
  <img alt="Tooltip in the results section" src="/gifs/resultsHover.gif" height="250"/>
</div>

### Hover titles
The titles of the section maintain short to improve the overall visibility. Nevertheless, hovering on them gives a more specific and detailed title of each section.

<div style={{
      display: flex;
      justify-content: space-around;
     }}>
  <img alt="Titles triggers by hovering in the duration between visit component" src="/gifs/visitsTitles.gif" height="250"/>
  <img alt="Titles triggers by hovering in the right-bottom corner" src="/gifs/lastTitles.gif" height="250"/>
</div>
