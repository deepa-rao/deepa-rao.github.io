## Welcome to my GitHub site

I'm Deepa Rao, a computational microbial ecologist, oceanographer, and science communicator. 

My GitHub site is a portfolio of analysis and useful code from lab experiments, field observations, and models.

Code in Python & R. 

[Link to Data Sci](https://github.com/deepa-rao/deepa-rao.github.io/blob/master/assets/img/Bokeh/data_vis.md).

## Interactive omic data analysis using Python + Bokeh
* Cultured algae under a matrix of iron and vitamin B12 concentrations to examine its metabolic response to dual nutrient limitation
* Analyzed proteomic data to identify significantly differentially abundant proteins using the power law global error model (PLGEM) approach (citation)
* Calculated metrics to compare normalized protein abundances across treatments; in this example, the low iron treatments -/+ B12.
* Using Bokeh, I customized code to generate MA plots (log2 average vs. log2 fold change) of proteins between two treatments, as well as the 1:1 line for comparison. 
* Highlighted specific protein categories: significantly differentially abundant (DAP), B12, iron (Fe), and cell cycle.
* Included hover-text to aid visual inspection of individual proteins (a few thousand in this figure), to connect the data with protein annotation and ORF id.
* Embedded Bokeh .html figure onto GitHub pages site for portfolio.

<iframe src="/assets/img/Bokeh/MA_lo_0_10_portfolio.html"
    sandbox="allow-same-origin allow-scripts"
    width="500"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
