# Duke-WBB-Offensive-Efficiency

## Overview
This study was conducted as part of my research for my Master's thesis at Duke. All work was completed independently. The thesis extract is provided below:

The purpose of this study is to assess the field goal efficiency of the Duke Women’s Basketball offense with data collected on possession by possession breakdowns. More specifically, the aim is to understand what features make the most efficient possessions, and how a coaching staff can utilize this feedback to optimize the offense. 

Studies like this are robust in the NBA, where data and resources are nearly unlimited. However, in the women’s college basketball space, this kind of work doesn’t publicly exist. This is in part due to a lack of available data, as well as, limited resources at the collegiate level. Because data science work is underused in women’s college basketball, a study like this could offer competitive advantage to programs who are able to leverage statistical tools to gain further statistical insight of themselves and their opponents before resources become more widely available in the sport. 

In order to proceed with this study, all of the data was hand collected from game film. Specifically, this analysis is run using data collected on offensive possessions from the 2022-23 Duke Women’s Basketball Season. The possessions of specific interest were those in which a field goal attempt was made. Possession features in the data set include: 

- location of the shot attempt
- player that took the shot
- number of passes in the half court
- number of paint touches
- number of times the ball changed sides of the floor
- possession type (half court, transition, baseline out-of-bounds, sideline out-of-bounds)
- numbers advantage (3 on 2, 2 on 1, etc), shot clock at time of attempt
- whether or not the possession was the result of an offensive rebound
- whether or not the field goal attempt was a make or miss

Using this data, I begin my investigation of offensive efficiency, first executing feature selection and then proceeding with model construction. Finally, I assess my model results, highlight key possession features, and offer offensive strategy modifications that look to improve overall field goal efficiency.

## Deployment
Step 1: For best user experience run using RStudio. Download here: [RStudio](https://posit.co/download/rstudio-desktop/)

Step 2: Fork the repository OR download the 'Portfolio Code'.Rmd and 'Duke WBB 22-23 Off Pos Data'.xlsx files from the repository

Step 3: Run the 'Portfolio Code'.Rmd

## Note for the User
The data has been updated since the conclusion of the thesis. The best model and predictions results may vary from the original conclusions.
