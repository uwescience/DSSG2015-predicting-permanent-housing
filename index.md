---
layout: home
---

<div class="home">
<div class="logo-bar">
</div>
</div>
  <h1 class="page-heading">Predictors of Permanent Housing for Homeless Families</h1>

**Project Leads**: Neil Roche and Anjana Sundaram, [The Bill and Melinda Gates Foundation](http://www.gatesfoundation.org/)

**DSSG Fellows**: Joan Wang, Jason Portenoy, Fabliha Ibnat, Chris Suberlak

**ALVA Students**: Cameron Holt, Xilalit Sanchez

**eScienc Data Scientist Mentors**: [Ariel Rokem](http://arokem.org), Bryna Hazelton


The Bill and Melinda Gates Foundation, together with [Building Changes](http://www.buildingchanges.org/) have partnered with King, Pierce and Snohomish Counties to make homelessness in these counties rare, brief and one-time. The goal of this project was to analyze data on enrollments in programs serving homeless individuals and families in these counties, to identify factors that predicted whether families would succeed in finding permanent housing and to investigate the ways families move between different programs. The partnership is particularly interested in using data to evaluate what types of programs are most successful and for which types of families.

De-identified individual records from 2011-2014 were extracted separately by each county from the federally-mandated Homelessness Management Information Services (HMIS) database and provided to the team as CSV files. The data representations were substantially different for each county, partly because of the different extractions and partly because of differences in what is recorded and how families are tracked in each county. Understanding these differences and wrangling the data to align it across the counties was a substantial undertaking.

We developed algorithms to identify families from the individual enrollments and to identify 'episodes' of homelessness that could span several back-to-back or overlapping enrollments in individual programs. We devised innovative ways to visualize and analyze the ways families move from program to program through the HMIS system, including interactive [Sankey diagrams](tinyurl.com/dssg-homeless) and trajectory plots (see below). These visualizations were particularly interesting and helpful to the county data leads, who have already used them to identify sources of coding errors and to evaluate some of their programs.

<img src="http://uwescience.github.io/DSSG2015-predicting-permanent-housing/images/PierceTrajectories.png" alt="Trajectories in Pierce county" style="width:300px;">

The automated analysis pipeline that the team developed exports clean data ready for statistical analysis across all three counties, enabling both in-depth studies and quick exploratory analysis to answer new questions as they arise. The Gates Foundation is working to incorporate the code so that it can continue to be used for new data as it comes in, and for new analyses.

  <h1><a href="{{site.baseurl }}/posts/">Project blog</a></h1>
