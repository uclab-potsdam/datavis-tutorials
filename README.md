# Data Visualization

**Hands-on tutorials for basic visualization techniques and the necessary data processing**

![cover](https://infovis.fh-potsdam.de/tutorials/cover.png)

Data visualization transforms datasets into visual and interactive representations. As we encounter growing datasets in various sectors we need to develop effective methods for making sense of data. Data visualization relies on computational means and our perceptual system to help reveal otherwise invisible patterns and gain new insights. Across various fields, there is great hope in the power of visualization to turn complex data into informative, engaging, and maybe even attractive forms. However, it typically takes several steps of data preparation and processing before a given dataset can be meaningfully visualized. While visualizations can indeed provide novel and useful perspectives on data, they can also obscure or misrepresent certain aspects of a phenomenon. Thus it is essential to develop a critical literacy towards data visualizations. One of the best ways to achieve this is to create them yourself!

## Tutorials

The following tutorials require basic familiarity with statistics and programming. They come as [Jupyter notebooks](https://jupyter.org/) containing both human-readable explanations as well as computable code. The code blocks in the tutorials are written in [Python](https://www.python.org/), which you should either have already some experience with or a keen curiosity for. 

The tutorials make frequent use of the data analysis library [Pandas](https://pandas.pydata.org/), the visualization library [Altair](https://altair-viz.github.io), and a range of other packages that you can find in the respective `requirements.txt` files in each tutorial. If you run these notebooks locally, you might want to run `pip install -r requirements.txt` first. You can view the tutorials as webpages, open and run them on [Deepnote](https://github.com/uclab-potsdam/datavis-tutorials) and 
[MyBinder](https://mybinder.org/v2/gh/uclab-potsdam/datavis-tutorials/HEAD), or download the Jupyter notebook files to edit and run them locally in your own environment. The first four tutorials lay the groundwork, after which five common data structures are covered:

1. **[Getting started](1-Getting-started/datavis1start.ipynb)**  Refresh your Python skills and meet Pandas and Altair
2. **[Visual encoding](2-Visual-encoding/datavis2encoding.ipynb)**  Learn how to transform data dimensions into visual variables
3. **[Data wrangling](3-Data-wrangling/datavis3data.ipynb)**  Load and parse different data formats and examine their contents
4. **[Interaction techniques](4-Interaction-techniques/datavis4interaction.ipynb)**  Add interactivity to visualizations and support data exploration
5. **[Temporal analysis](5-Temporal-analysis/datavis5time.ipynb)**  Analyze temporal data and present time spans, trends, and patterns
6. **[Text processing](6-Text-processing/datavis6text.ipynb)**  Extract common words, filter them by type, and them in context
7. **[Many dimensions](7-Many-dimensions/datavis7multidim.ipynb)**  Combine datasets and create multidimensional visualizations 
8. **[Network analysis](8-Network-analysis/datavis8networks.ipynb)**  Load network data, examine graph metrics, and visualize their structure
9. **[Geovisualization](9-Geovisualization/datavis9geovis.ipynb)**  Work with geospatial data and render different kinds of maps 

## Credits

The tutorials were created by Marian Dörk for Data Visualization courses at Fachhochschule Potsdam. The first set of tutorials were created during the special summer semester in 2020 when we had to shift to remote teaching. Since then the tutorials have been gradually updated over and over again. Many thanks to Fidel Thomet, Jonas Parnow, Viktoria Brüggemann, Ilias Kyriazis et al. of the [UCLAB](https://uclab.fh-potsdam.de) for frequent feedback on the tutorials and to the many students at FH Potsdam who worked through pencil exercises and helped refine the tutorials over the years. Special thanks also to the many generous creators of the various open source software packages used throughout the tutorials.

The notebooks are released under the [Creative Commons Attribution license (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

If you encounter any errors or have any suggestions for improvement, feel free to ~[send an email](mailto:marian.doerk@fh-potsdam.de)~ fork this repository and send a pull request.
