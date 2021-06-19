# cst383-final

## Introduction 
The purpose of this project is to try to determine the number of wins that a NBA Basketball team will have during the regular season by analyzing the overall season statistics. This prediction set is used for the current NBA season and no other year statistics would be used. 

When our group decided that we wanted to demonstrate that we could predict overall win/loses based on NBA teams, we realized that any future data used would be challenging for this project. To formulate an appropriate hypothesis, our plan was to use a current year worth of statistics and then to analyze that data and see if our results could be close to what the actual results were. Instead of using previous years data to predict future results, this approach seemed more manageable.

Although actual results would be known for teams wins and losses, our hypothesis is that we can hope to predict season record of individual teams by analyzing statistical data and then compare our results with the actual records. This approached seemed appropriate for the size and scope of the project and allowed us to directly see if our hypothesis was correct or not.   

## Selection of Data
The first challenge of this project was to find quality data to use. Our team went back and fourth on the goal of the project and we knew that we first wanted to find quality to use based off of a rough idea of what we wanted to solve. We decided that we were able to find sports statistical data and moved forward with trying to predict wins/losses based off of our data.  

We collected 3 key pieces of data to help with our projects. We collected 3 comprehensive .csv files including statistics from box scores, team percentages and advanced stats. Projection data will be used from each source of statistics to help us get a better gauge of win percentages.

A challenge with our dataset was to understand what data would be best to overall use to help us make better predictions. Our team also spent significant time understanding the data and what was available to us. Once our team felt comfortable with the dataset and believed we could accomplish our goal, we moved forward with our project.

## Methods
To begin our project, we begun to import our data that our team decided on. We all felt that the most important part of starting a project was to fully understand the data that we were working with and to make sure we imported the correct information. To begin, we imported the data and then used df.info() and df.describe() to verify our data. We also were able to use our IDE tools to inspect additional data. 

Furthermore, an additional step in our research was to verify that we didn't include any Nulls in our data. For the most part, our data was very complete after import and we were satisfied with everything that we had to work with. 

Additional, we started to break out our columns a further to see what we were accurately working with. Most of our columns included overall rank, games played, mins played, field goals, field goal average, three pointers, three point average as well as offensive and defensive rebounds and blocks and points.
Our team was able to plot a lot of this information to not only verify our data but to get a better understanding of what we were using to make further projections.

Once we were complete with initial analysis we mainly plotted offensive rating with wins and loses to get a baseline of data. Obviously, we concluded that teams that were efficient on offense would essentially result in more wins for that individual team. Plotting this information was very beneficial because we could get a quick glance of estimated results.

After plotting offensive results we were able to plot individual team wins to get more understanding of our data. We separated the data to plot two distinct graphs of not only team wins but only team loses. Using this technique allowed us to get a good gauge of team results. When we combined scatter plots we were able to visually see teams that were 500% and get a rough estimate of the overall league.

We further used our data to use logistic regression to find team wins. We based this data using a few columns such as teamEFG, opptEFG, teamTO, opptTO, teamOREB, teamDREB, teamFTF, opptFTF and overall outcome. We further trained out data using train_test_split and created a logistic regression model. 

Using the above techniques we were able to use a loss/win scenario and map individual results to IDs of our data.


## Results
Our results were consistent with what we expected in that we could use prediction models to get a better gauge of overall team win/losses. Although this research was based on existing results we were happy with our research and hope to expand on this in the future.

Our overall goal moving forward is to use historical data from additional years to provide accurate projections for the future. Our team struggled with understanding the best way to do this since teams adjust each and every year so it was difficult to gauge how each team would do.

Our team concluded that to provide better projections we would need to individually break down players and then combine those stats to each team to get more accurate projections. 

Also, we spent a lot of time trying to get different results with different column stats so if we researched more years than we would have a better understanding moving forward.

Moving forward, this was a challenging project and although we struggled with many aspects of this assignment, we also had good experiences with validating data and trying to predict wins/losses.

## Discussion
The most interesting part of this project and something our group discussed in great detail is how we could apply data in this capacity to future seasons. From our dataset, we used previous historic data of the current season to set up a baseline of how we think each team should have done in the standings. In actuality, this approach should be done for future seasons to give predictions based off of unknown statistics. Although the challenge with this is that teams change per year, new players/coaches, and the statistics might not carry over directly.

For future discussions, our team suggested for an improved project and something that would take a lot more time but out of scope of this project would be to analyze years of NBA statistical data and formulate what column data would be more appropriate to further guess outcomes. A lot of the information we used were different offensive/defensive based measurements which seemed to be helpful for this assignment but further rigorous data analysis might show which column data is more impactful. 

## Summary
In summary, our team was able to apply a lot of the techniques we learned this semester into this project and we were happy with our results. It was an interesting exercise to not only chart out statistics but to try to formulate answers based on our data. 

A lot of lessons learned by this assignment but not only using correct techniques but also using the correct data. We took on a project that was probably well beyond the scope of this required assignment but our team felt that our initial results could lead to further research. Our team discussed that our data was based on one single year and our hypothesis was compared on those results.
