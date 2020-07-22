# Assignment 3 & 4 Critique by Design

## The Original Visualization

I found this article on [Clean Technica](https://cleantechnica.com/2019/08/16/tesla-model-3-12-4-of-all-norwegian-vehicle-sales-january-july-2019/). This is an article that discuss the EV sales in Norway and how Tesla Model 3 is dominating the new vehicle market in Norway. It provides a simple visualization of the sales figures on new vehicles sold in Norway during the first half of 2019. I have huge interest in the automotive industry and keep a close look at the latest developments, one of which is electrification. Therefore, I'm very interested in how EV sales are visualized and narrated to general readers. This article showed a market that aggressively pushing towards electrification and is illustrative of what the future of auto market could look like. Unfortunately, the data visualization does not do the job right, so I want to redo it to make it nicer.

## Wireframes and Peer Feedback

After doing the critics, the first though is to use pie chart instead of bar chart since pie chart is the most common way of showing comparison between percentages. Since I suspect readers of this article cares more about the percentage comparison instead of the actual sales figures, I keep the percentage value but discard the actual sales numbers. Also the color scheme is not sufficient with only EVs highlighted but mixed models not differentiated from pure ICE (internal combustion engine) models. Red and blue is also not the best color that's intuitive to readers. Therefore, I choose green for pure EVs, blue for mix of electric and ICE vehicles and grey for other vehicles. This color scheme is more intuitive to people's perception and greyed out other vehicles reduce distraction.

With these thoughts in mind, I've made the first sketch of the redesigned chart:
<iframe src='https://flo.uri.sh/visualisation/3252797/embed' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3252797/?utm_source=embed&utm_campaign=visualisation/3252797' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

After the fisrt draft, I immediately realized improvements:
* I should regroup the pieces. I don't have to rank them by sales, but rather group EVs and Mixed models together respectively. Doing so will make it more intuitive for readers to see how much the market is made up of electric vehicles, which also helps the statement in the article that EVs makes up 38.4% of the new car sale in Norway.
* When using the pie chart, the exact percentage number is not that important sicne people will just comprehend the percentage by how large each piece is instead of looking at the numbers. For a cleaner view, I omitted the percentage values as well.

Then, I've come up with the second draft:
<iframe src='https://flo.uri.sh/visualisation/3253260/embed' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3253260/?utm_source=embed&utm_campaign=visualisation/3253260' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

Then, I presented both drafts to my friends and asked them a few questions. Here's come selected answers:
### Can you tell me what you think this is?
It looks like a chart showing car sales in Norway where a lot of EV and hybrid vehicles are sold.
### Can you describe to me what this is telling you?
A huge portion of cars sold in Norway are electric or hybrid.
### Is there anything you find surprising or confusing?
Norway sells a lot of EVs and hybrids, but the car model names are clumped together and doesn't make any impression of what they are.
### Who do you think is the intended audience for this?
People who cares a about EV sales and marker adoptions.
### Is there anything you would change or do differently?
I would add either logos or something else that allow people to understand what those models are. I would also make the labels clearer to see.

## Final Visualization
From the feedbacks, I've realized the following improvements:
* Nobody notice that Tesla Model 3 sale is supposed to be highlighted as well as suggested in the article, so I should highlight Model 3 sales as well.
* People can't get the percentage of EV sales as suggested to be 38.4% in the article, I should somehow make those numbers visible as well.
* I need to change the way the labels are presented so its easier for people to see.
* I can include pictures of each model so the readers can quickly recall what they are.
* Even the percentage number doesn't matter that much for readers: people feel the size of the pie pieces.

With these improvements, I made my final version of the visualization:
<iframe src='https://flo.uri.sh/visualisation/3253301/embed' frameborder='0' scrolling='no' style='width:100%;height:750px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3253301/?utm_source=embed&utm_campaign=visualisation/3253301' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

In this final version, I've adopted a double ring design that also summarize EVs, mixed and ICEs. Since free flourish doesn't allow category legends for pie chart, doing so also helps get rid of the legends. This visualization now both highlights Model 3 sales and shows the percentage of EV sales which helps the narratives of the original article. I've also included pictures of each model in the pop-up note so readers can quickly recall what those models are.
