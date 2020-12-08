---
title: Genomic analysis of SARS-CoV-2 spread on Wisconsin university campuses.
authors:
  - Gage Moreno
  - Katarina Braun
  - Thomas Friedrich
  - David O'Connor

authorLinks:
  - https://twitter.com/GageKMoreno
  - https://twitter.com/KATarinambraun
  - https://twitter.com/tcfriedrich
  - https://twitter.com/dho
affiliations: 


license: "CC-BY"  
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "http://localhost:4000/ncov/wisconsin/statewide?c=campus&p=Phylogeny" # must be accessible to the auspice server running the narrative

abstract: "SARS-CoV-2 genome sequencing helps us to infer patterns of viral transmission through space and time. Importantly, viral genetic diversity can also be used to infer epidemiological parameters, such as the number of introductions into a community, independent of direct clinical testing. Here we analyze a set of 363 SARS-CoV-2 genomes collected from three Wisconsin university campuses – UW-Madison (n=242), UW-Milwaukee (n=91), and Marquette (n=11). All three of these college campuses have experienced surges in SARS-CoV-2 case counts since the beginning of the fall semester. To date, UW-Madison has reported 3,386 cases, UW-Milwaukee has reported 621 cases, and Marquette has reported 433 cases. Cases rapidly increased on all three of these campuses mid- to late-September and have since largely plateaued."
---

<!-- Comment tags like these are not rendered, they're just helpful for you -->
<!-- Known 'gotcha' bug: ensure that links always end in a 'letter' (a period counts). If some kind of text doesn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 1 -->
<!--  Each slide MUST start with a link to a specific view of the dataset (must match the `dataset` specified above) -->
# [SARS-CoV-2 at UW-Madison](http://localhost:4000/ncov/wisconsin/statewide?c=campus&f_campus=UW-Madison&p=treeonly)

<!-- This is left-side text -->
The University of Wisconsin - Madison (UW-Madison) is Wisconsin’s flagship university, located in Madison, WI, which is encompassed by Dane County. UW-Madison’s reopening plans, called “Smart Restart”, which included bi-weekly testing is required for students who live in University Housing and optional testing for students in off-campus housing. Part of the “Smart Restart” included a “Badger Pledge” which required students to take an online training and comply with the guidelines established by the “Smart Restart”. More information on the smart restart can be found [here](https://covidresponse.wisc.edu/plan/).

<br>

By Mid-August, most of the upperclassman had returned to campus. Freshman move-in occurred at the end of August and into early September. At the start of the semester an increase in SARS-CoV-2 cases became evident by 

<!-- There is right-side text on this slide -->
```auspiceMainDisplayMarkdown
# SARS-CoV-2 cases over time at UW-Madison  
![UWmadisoncases](UWCases.png])

Screenshot from https://covidresponse.wisc.edu/dashboard/
```

<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 1 -->
<!--  Each slide MUST start with a link to a specific view of the dataset (must match the `dataset` specified above) -->
# [SARS-CoV-2 at UW-Madison](http://localhost:4000/ncov/wisconsin/statewide?c=campus&f_campus=UW-Madison&p=treeonly)

<!-- This is left-side text -->
An overview of all UW-Madison viruses sequenced with all currently sequenced Wisconsin virueses. The majority of UW-Madison viruses associate in one large 20C clade, and tend to be isolated from other viruses within Wisconsin. This suggests that the outbreak that occurred on UW-Madison’s campus was largely isolated, and has not spilled over into the broader Dane County community. However, continued sequencing from later timepoints is needed to determine if the outbreak has remained contained. 


The University of Wisconsin - Madison (UW-Madison) is Wisconsin’s flagship university, located in Madison, WI, which is encompassed by Dane County. UW-Madison’s reopening plans, called “Smart Restart”, which included bi-weekly testing is required for students who live in University Housing and optional testing for students in off-campus housing. Part of the “Smart Restart” included a “Badger Pledge” which required students to take an online training and comply with the guidelines established by the “Smart Restart”. More information on the smart restart can be found [here](https://covidresponse.wisc.edu/plan/).
<!-- There is NO right-side text on this slide -->


<!-- ############ SLIDE BREAK ############# -->
<!-- SLIDE 2 -->
# [SLIDE 2 TITLE](http://localhost:4000/ncov/wisconsin/statewide?branchLabel=aa&c=campus&f_campus=UW-Madison&label=ORF1a:R1170C")

<!-- This is the left-side text -->

[Including a link as an example; always end the line with a period or other 'letter' character](google.com)!
Hi ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<!-- There is NO right-side text on this slide -->
<!-- ############ SLIDE BREAK ############# -->

<!-- SLIDE 3 -->
# [SLIDE 3 TITLE](http://localhost:4000/ncov/wisconsin/statewide?c=campus&f_campus=UW-Madison&mutations=ORF1a:R1170C)

<!-- This is the left-side text -->

[Including a link as an example; always end the line with a period or other 'letter' character](google.com)!
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<!-- There is NO right-side text on this slide -->
```auspiceMainDisplayMarkdown
# Example using markdown for the right side  
We can also replace the right side view with whatever markdown contents we choose, including links, images, etc.
```