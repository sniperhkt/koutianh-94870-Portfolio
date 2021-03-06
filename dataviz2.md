# Assignment: Visualizing Government Debt

## Part 1: Working with web-based visualization tools and data

Here's the embeded data visualization from OECD:
<iframe src="https://data.oecd.org/chart/61N6" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/61N6" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>


## Part 2: Working with Flourish

This is the grid of lines chart generated by Flourish visualizing the same data set from OECD:
<iframe src='https://flo.uri.sh/visualisation/3182545/embed' frameborder='0' scrolling='no' style='width:100%;height:1600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3182545/?utm_source=embed&utm_campaign=visualisation/3182545' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

I've also created a race chart showing the ten contries with the most and the least debt-to-GDP ratio using the same data set:
<iframe src='https://flo.uri.sh/visualisation/3183024/embed' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3183024/?utm_source=embed&utm_campaign=visualisation/3183024' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>
However, to create this data set, I need to parse the data using this [python script](Assignment-2-Data-Parsing.ipynb).

## Compare/Contrast Different Visualizations

The data comes from [OECD data base on government debt](https://data.oecd.org/chart/61Nz). It contains the government debt data from 1995 to 2018 for 35 countries, but some of the countreis does not have debt data for all years between 1995 and 2018. According to the visualizations, most countries shown here have rising debt-to-GDP ratio and the major growth in debt start around the year of 2008, when the global financial crisis took place. There are a few of them that managed to keep their debt at a low level such as Estonia, Chile and Sweden.

The bar chart in part 1 gives a clear listing of government debt for a list of countries and how they compare against each other, whereas the grid of line chart gives an overview of how each contries' government debt evolve over the years. There are two dimensions this dataset conveys: across all contries and across time. The bar chart gives a clear sense of comparison between countries but lose the ability to see over time while the grid chart gives an panel view of all contries over time but does not show clear comparision between contries.

The straight forward way of showing both dimensions is to combine all line chart into the same picture - a single line chart with multiple lines. However, doing so will lead to a single chart with too many information and many lines overlapping each other. Even with carefully chosen color scheme it takes a long time for viewers to digest. Therefore, to introduce the time dimension over the comparision between countries, animation kicks in and does the job very well, which results in the choice of racing bar chart. The animated time axis is very intuitional for viewers to perceive the evolution over time as time is simulated here. The bar chart gives a clear comparision as well. I chose to only show the most and the least ten countries also to reduce noise and help viewers comprehend the information faster. The racing bar chart may omit some details and makes it harder for viewers to see all numbers compared with two previous charts, but in return as tradeoff, the racing bar chart is intuitive for viewers to see both dimensions of the dataset.
