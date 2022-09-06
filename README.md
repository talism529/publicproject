a new analysis which shows what types of generators are producing electricity at different times of day. This manager mentions that they think an intern had started something similar a few years ago and sends you the file SPPscrape_new.py along with the following message:

Here is the code file I mentioned earlier. I'm not sure what it does or if it is even correct, so feel free to make any changes to it that you feel are necessary (or start from scratch).

What we want to see here are two charts. The first chart will show the share of electricity produced by each fuel type during the highest-load hour of each day (load is how much electricity is being used at a point in time). The second chart will show the same statistic but for the lowest-load hour of the day. Here are a few notes:

If a fuel type is broken out into multiple series in the raw data then combine those series before plotting
The x axis should start at Jan 1st and end at Dec 31st
The y axis label should be "% of Total Generation"
We may want to publish the chart in a report, so it should look nice and be easy to interpret
We want to see the charts for 2020, but we plan to reuse this code next year, so it should be as easy as possible to change the year
You will be the owner of this code from now on, so make sure it is up to your standards for clarity and neatness
Guidelines
Here are some guidelines for completing this project:

The only restrictions for this project are that any packages you use must be freely available, and you must complete the project independently
There is no time limit for this project, but plan to spend less than 4 hours working on it. If you don't complete it during that time we can still discuss the progress you made. If there is something you want to do but run out of time, add a comment that starts with TODO: and explains what you would do given more time.
There is not a "right answer" that we are looking for. This is designed to be like a task you would be assigned if you join our team - no one has done it before, so we don't really know what it should look like. Since you are the first person completing this task, you get to choose how exactly to go about it.
Next Steps


Tip
You can find the highest- and lowest-load hours of the day by finding the average load across each hour. Here is an example:

Hour 1: Load is 2000 MW for 15 minutes and then a blackout occurs (load is 0 MW for the rest of the hour). 2000 * 0.25 = 500
Hour 2: Load is 800 MW for 30 minutes and 700 MW for 30 minutes. 800 * 0.5 + 700 * 0.5 = 750
In this example, Hour 2 is the highest-load hour.

