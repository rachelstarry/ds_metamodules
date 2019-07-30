# Meta-Module #7: Data Visualization

This “meta-module” introduces some tools, methods, and best practices for representing information using visual means. 

**Estimated Completion Time = 5 hours**

## Outcomes

* Increased understanding of the value and benefits of data visualization
* Increased familiarity with tools and best practices for creating accessible data visualizations

## Introduction

While data analysis and visualization workflows can vary widely across disciplines, the field of information visualization has achieved consensus on certain practices and approaches.<sup>[1](#note1)</sup> On the one hand, [exploratory data analysis](https://en.wikipedia.org/wiki/Exploratory_data_analysis) includes several common processes, from summarizing data in order to understand how it is organized and making transformations where necessary, to visually exploring the data in order to illuminate potential underlying patterns. Explanatory data visualization - or "storytelling with data" - varies somewhat more in terms of the tools and platforms used to integrate scholarly or journalistic narratives with summary tables, charts, and maps.

This module places a greater emphasis on best practices for creating accessible data visualizations and selecting appropriate chart types for different kinds of data than on particular visualization workflows or tools. The readings and resources do, however, offer an opportunity to practice data wrangling and visualization skills using several different online platforms, and many library research guides offer guidance on desktop software such as Tableau or programming solutions like R and Python (see Additional Resources, below).

Notes:</br>
<sup><a name="note1">1</a></sup> Meirelles, Isabel. 2013. *Design for Information: An Introduction to the Histories, Theories, and Best Practices behind Information Visualizations*. Beverly, MA: Rockport Publishers. </br>

## Activities

- [ ] Complete [SSRC Module 7: Basic Visualizations](https://labs.ssrc.org/dds/articles/5-building-digital-collections/)

- [ ] Additional Readings
	* Cesal, Amy. June 26, 2018. "Accessible data viz is better data viz." *Storytelling with Data*. https://www.storytellingwithdata.com/blog/2018/6/26/accessible-data-viz-is-better-data-viz **◊  Estimated Read Time = 6 minutes**
	* Grosser, Zach. January 10, 2018. "Accessible Colors for Data Visualization." *Medium*. https://medium.com/@zachgrosser/accessible-colors-for-data-visualization-2ad64ac4ee7e **◊  Estimated Read Time = 5 minutes**
	* Kosara, Robert. March 2, 2017. "Sonification: The Power, The Problem." *EagerEyes*. https://eagereyes.org/techniques/sonification-the-power-the-problems **◊  Estimated Read Time = 4 minutes**
	* Kosara, Robert. 2017. "An Argument Structure for Data Stories." *Short Paper Proceedings of the Eurographics/IEEE VGTC Symposium on Visualization (EuroVis)*. https://kosara.net/publications/Kosara-EuroVis-2017.html **◊  Estimated Read Time = 20 minutes**
	* Nussbaumer Knaflic, Cole. April 14, 2014. “Exploratory vs explanatory analysis.” *Storytelling with Data*. https://www.storytellingwithdata.com/blog/2014/04/exploratory-vs-explanatory-analysis  **◊  Estimated Read Time = 3 minutes**
	* Simmon, Robert. August 12, 2013. "Subtleties of Color: Different Data, Different Colors." *Visually*. https://visual.ly/blog/subtleties-of-color-different-types-of-data-require-different-color-schemes/ **◊  Estimated Read Time = 5 minutes**

- [ ] Explore [From Data to Viz](https://www.data-to-viz.com/)
	* Choose a dataset from [Gapminder](https://www.gapminder.org/data/). You can search or browse data by "indicators" such as income, life expectency, or CO2 emissions for 191 countries.
	* Open your dataset - which should be a .csv or .xlsx file - using your spreadsheet software of choice, such as Excel or Numbers (a free and open-source alternative called Calc is available from [LibreOffice](https://www.libreoffice.org/discover/calc/)). What kind of information is included in your selected dataset?
	* Explore your dataset by stepping through the flowchart on [From Data to Viz](https://www.data-to-viz.com/), considering the following questions for some or all of the variables in your dataset:
		* Is your data numeric, or is it categorical? ([Read more about numeric vs. categorical variables here.](https://eagereyes.org/basics/data-continuous-vs-categorical))
		* Does your dataset include time-series ([also called longitudinal](https://www.nlsinfo.org/content/getting-started/what-are-longitudinal-data)) data? If so, what time periods are covered and how frequently was data collected?
		* What kinds of questions would you want to ask of your selected data? Think of one question in particular: how many variables would you need to visualize in order to answer this question? The number of variables required to answer a question can have a significant impact on the kinds of charts available to help you visualize the data. 
		* Finally, select and explore at least two types of charts with which you are not already familiar. Read more about the chart type, including its affordances and caveats for using it, and browse the gallery of examples. 

- [ ] Develop your visualization skills using [RAWGraphs](https://rawgraphs.io/) <br>
	RAWGraphs is an open-source data visualization framework developed by the DensityDesign Research Lab. It was created with the goal of making complex data visualization easy for everyone. 
	* Watch the "[Introduction to RAWGraphs](https://rawgraphs.io/learning/introduction-to-rawgraphs/)" video on RAWGraphs' [quick reference guide](https://rawgraphs.io/learning/).
	* Read more about preparing your data for visualizing, in "[Stack your unstacked data (meet the unpivoter)](https://rawgraphs.io/learning/stack-your-unstacked-data-meet-the-unpivoter/)." The data you selected from Gapminder previously may be in "unstacked" form, particularly if it includes time-series data (many columns that each represent data collected in a particular year or other time period). 
	* Import your data into the [RAWGraphs app](http://app.rawgraphs.io/). Try stacking your data using the "unpivoter": for example, many of the Gapminder datasets have a column with the name of a country and many other columns with data collected over time, such as literacy rates for different demographic groups or energy consumption in kilowatt hours. If this is the case, you can stack on the column "Country" in order to visualize your dataset in RAWGraphs. (Caveat: some Gapminder data may be too large to import into RAW; if you experience difficulty importing your data, copy and paste a subset of the data instead.)
	* Using what you learned about your data from your exploration of From Data to Viz, select one or two chart types and practice creating a visualization in RAWGraphs, by selecting variables to visualize. For help creating your graphs, refer to the "how-to" guides for various chart types on [RAWGraphs' Learning page](https://rawgraphs.io/learning/).

- [ ] "Meta" Questions to Consider
	* What concerns about accessibility are raised in the readings? What might alternate data representation techniques such as sonification offer in terms of accessibility to users with visual impairment? 
	* How might the process of developing visualizations that will be shared online - i.e. viewed on a screen - differ from the creation of visualizations that will be encountered exclusively in print media? What other factors might you need to consider from the perspective of the user when you plan to publish data visualizations primarily in digital form?
	* Given your understanding of basic data visualization techniques as introduced in these readings and resources, what kinds of issues might researchers across all disciplines face when developing visualizations? Can you imagine data visualization challenges particular to individual disciplines that you engage with in your library?
	* How does your library support researchers in finding data, and how do (or how might) you support researchers in the subsequent steps of transforming that data and preparing it for visualization?

- [ ] Short Reflection
	* Take a few minutes and try to articulate what you will take away from the readings, activities, and resources covered in this module. What is one concept that you feel you now understand better? One topic that was completely new to you? One question you would like to explore further? 

## Additional Resources

### Selected library research guides on Data Visualization:

* Duke University: [Data Visualization](https://guides.library.duke.edu/datavis)
* George Mason University: [Data Visualization](https://infoguides.gmu.edu/data-visualization)
* San Jose State University: [Data Visualization](https://libguides.sjsu.edu/datavis)
* Temple University: [Data Visualization](https://guides.temple.edu/dataviz)
* UC Los Angeles: [Data Visualization](http://guides.library.ucla.edu/data-visualization)
* UC San Diego: [Data Visualization](https://ucsd.libguides.com/data-viz)
* University at Buffalo: [Data Visualization](https://research.lib.buffalo.edu/dataviz/home)
* University of Illinois at Urbana-Champaign: [Visualize Your Data](https://guides.library.illinois.edu/visualize-your-data)
* University of Nebraska Omaha: [Data Visualization](https://libguides.unomaha.edu/c.php?g=718688)
* University of Texas: [Data Visualization](https://guides.lib.utexas.edu/data-visualization/home)


### Data Visualization blogs

* [Storytelling with Data](http://www.storytellingwithdata.com/), blog by Cole Nussbaumer Knaflic
* [Visualising Data](http://www.visualisingdata.com/blog/), website and blog by Andy Kirk
* [Flowing Data](https://flowingdata.com/), blog by Nathan Yau
* [Information is Beautiful](https://informationisbeautiful.net/blog/), blog by David McCandless
* [Day Doh Viz](https://www.amycesal.com/day-doh-viz-all/), data visualizations in play-doh by Amy Cesal
* [Chartable](https://blog.datawrapper.de/), blog by Datawrapper
* [Graphic Detail](https://www.economist.com/blogs/graphicdetail), The Economist's data journalism blog
* [Modern Data](https://moderndata.plot.ly/), Plotly's data visualization blog
* [Xenographics](https://xeno.graphics/), weird but (sometimes) useful charts

### Data Visualization galleries

* [US Census Bureau Gallery](https://www.census.gov/dataviz/)
* [Tableau Public - Viz of the Day](https://public.tableau.com/en-us/s/gallery)
* [Visually - Staff Picks](https://visual.ly/staffpicks)
* [Visual Complexity](http://www.visualcomplexity.com/vc/)
* [Information Is Beautiful Awards](https://www.informationisbeautifulawards.com/showcase?award=2018&pcategory=winner&type=awards)
* [Visualizing.org](https://www.visualizing.org/)
* [The Atlas](https://www.theatlas.com/)