---
layout: default
title: Final Projects
# parent: Syllabus
has_children: True
nav_order: 6
---


# Final Projects
{: .no_toc }

1. TOC
{:toc}

---

## Learning Objectives   

By the end of this project you will be able to:  

* Formulate a Geographic Analysis Scenario
* Identify geospatial datasets appropriate for the geographic analysis
* Create a directory / geodatabase of datasets for the project (ensuring spatial and tabular data integrity)
* Conduct GIS analyses that will demonstrate your knowledge of GIS analysis concepts and software tools
* Visualize your results (maps) and workflow (model/flow chart) and discuss them in a brief report
* Follow a project proposal to until the project is successfully completed
* Build teamwork skills

---

## Deliverables    

The Project is due on the last day of term, **Wednesday June 22nd**.  There is also a Final Project Proposal that is due **Tuesday June 14th**.  The proposal will count as a 10% of your total Final Project grade.  Deliverables for this project will consist of the following:  

* Project Proposal

* Project Submission
    * A written report
    * Maps/charts visualizing your results
    * A flowchart visualizing your methodology

---

## Groups 

This is intended to be a group project.  I suggest you work in a groups of 3.  Groups larger than 4 are **not allowed**.  If you are looking to join a group, try making a post to the **Final Project Group Search** discussion page on canvas, list any topics you might be interested in working on.  If you are still having trouble finding a group try reaching out to your TA for assistance.

I encourage you to work in groups, however I also recognize group work can be very difficult for some, especially those taking the course online.  You may work alone if desired **but** you must request approval first.  Choosing to work alone **will not** lower the expectations for your project.  Your project will be evaluated using the same standards as group projects.

---

## Project Workflow

### Project Proposal: Explore Ideas and Acquire Data
{: .no_toc }

The proposal is intended to get you thinking about the project sooner rather than later, so you aren't stuck scrambling at the last minute.  See the [Project Proposal](docs/Project_Proposal.md) page for details.  The proposal is due **Tuesday June 14th**

Download and format your data during this step. Review the datasets and determine which layers and associated attributes you will need for your study. Pay special attention to the format of the data, and to the projection information before starting your analysis.  It is important to insure you can access the desired data before starting your project!

 
### GIS Analysis   
{: .no_toc }

The project should have a higher level of complexity than any of the four labs you completed during the course. Think about all the operations and tools that you have learned in the course, and apply these to your particular data and GIS analysis topic. A list of potential analysis operations includes:  

* Calculation of areas
* Joining tables
* Select by attribute/location: various queries
* Field calculation
* Buffers, dissolves, merges
* Overlay tools: clip, erase, union, intersect
* Raster overlay & reclassification
* Working with DEMs (elevation, slope, aspect)

It might be beneficial to do your project in Model Builder.  You are not required to do so, but it could be helpful for storing your workflow, which will make it easier to remember/describe your methods.

 
### Flow Charts    
{: .no_toc }

As you go through your GIS Analysis steps, document what you are doing and the specific operations you are performing (or use model builder!). You will produce a flow chart of your analysis and include it in the report.  If you use model builder for your analysis, this can serve as the basis for your flowchart, but you should translate it into an easier to follow an more aesthetically pleasing format for the final submission.

There are a number of ways to create flowcharts.  You can draw them by hand, you can use power point, or you can try [Diagrams.net](https://app.diagrams.net/).  This site allows you to make aesthetically pleasing flowcharts quickly and easily, the video bellow gives you a quick overview of how to use the too.


<iframe width="560" height="315" src="https://www.youtube.com/embed/jq5NxMpOSKI?start=135" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

 
### Data Visualization  
{: .no_toc }

You will need to make a series of maps/charts (number and type(s) depends on the specific analysis) to visualize your methods and final results.  These visualizations must follow the conventions of data classification and data display as learned in the course, and include all relevant map elements (legend, title, scale, north arrow, sources, insets/reference maps where necessary etc.) and take into consideration cartographic design principals (lecture in class on design).  

* Submit full resolution copies of each visualization (flowchart, maps, charts).  These will be evaluated for aesthetic quality and effectiveness at conveying your findings.  The full resolution copies are required just in case the embedded figures in your project report are not clear enough to read.

### Written Report
{: .no_toc }

Each group must produce a written report detailing their project.  The report should contain the flowchart, maps, charts, and/or tables embedded in the document with in text references to the visualizations where applicable.  The report should have the following sections:

**Introduction** – What is the problem? Why should we care?  Briefly introduce the scope of the issue you are addressing and conclude your introduction with your research statement.

* **Research Statement** – What is/are the specific question(s) you are looking to address?

**Data Sources** – What data are you using & where did they come from? What type of data are you working with (raster, vector, tabular)?  What’s the scale & resolution, is these limiting factors?  Are there any issues or special considerations with this data set?  A table might be a useful way to help summarize this section concisely.

**Methods** – What did you do? Why did you do it?  Explain the analysis steps you took and justify the choices you made in your analysis.  You can rely heavily on your flow charts for explaining the methods.  You don’t need to detail every little step, be brief but throughout.
* Don’t Say things like: “We doubled clicked the buffer tool and set Layer A as the input. We set the buffer distance to 1000 meters and clicked dissolve all.  We set the output name as Layer B and hit run.  Then we merged Layer B with Layer C naming it Layer D”
* Instead Say: “We buffered Layer A by 1000 m because (justification). Then we merged it with Layer C”
* **Flowchart** is best included here!

**Results** – What does your analysis say? Describe the general patterns and trends that your analysis yielded.
* Maps/charts go here!

**Conclusions** – What are the overarching conclusions? Did you find what you expected?  Did you answer the research statement?  What are some potential future analysis that could result from this?

**Bibliography** – Cite any data sources used.  Also cite any relevant literature.  It is not expected that you conduct a literature review, just make sure to cite any you do use. Reference them in a consistent format

There is no word/page count.  You can keep the report brief, just be thorough.  Make sure you explain and discuss the key points.

---

## Project Rubric

|       Category        |                                                                                                                                                 Details                                                                                                                                                  |Points |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
|**Analysis**           |Considers the project holistically (GIS Analysis + Interpretation)<br>Was the data projected correctly, were appropriate steps taken, are there missing steps, logical flaws, obvious errors?<br>How thorough & rigourous was the analysis<br>Needs to be more than just a re-hash of a lab assignment<br>|**60** |
|**Visualization**      |Are the maps, charts, and diagrams effective and aesthecially pleasing<br>Do they follow stylistic principals outlined in [lecture](https://june-skeeter.github.io/Module4_GEOS270/docs/Content_Part1.html)                                                                                               |**60** |
|**Report Content**     |Does the report effectively convey the problem, explain the anaysis, discuss the results, and present conclusions/future research<br>Do they have each section as outlined on the proejct page                                                                                                            |**60** |
|**Novelty & Relevance**|How unique/relevant is the topic/analysis<br>Did groups come up with their own idea substantially build on one of the ideas presented                                                                                                                                                                     |**30** |
|**Data & Bibliography**|Are the data sources approrpriate for the analysis<br>Did they detail data sources and cite any sources used                                                                                                                                                                                              |**15** |
|**Proposlal**          |Proposal is makred for completeness & effort (each section filled & project idea conveyed).                                                                                                                                                                                                               |**25** |
|**Total Score**        |   