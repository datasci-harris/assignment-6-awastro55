# Data_Skills_F2019_assignment_6

__Due Date: Tuesday, December 3rd before midnight__

Your assignment for this week will combine all of the data visiualization skills we've practiced for the last few weeks, with some data from our presenter on Thursday.

__The Data:__

As Jessica Kelly showed us last week, the Urban Institute hosts an open data portal.  Researchers at Urban clean and assemble a wide variety of data, and then make the organized data available for download.  In this case, you will retrieve college data from the Education Data Portal:

https://educationdata.urban.org/data-explorer/colleges/

You must use their interface, which builds a SQL query behind-the-sceens as you select options, then returns custom-built csv documents to you for download.  Certain data is only available for certain years; in this case we will be working with the date ranges 2001-2016, because that range enables a large number of options.

Depending on the options you select, you may receive more than one data file that needs to be merged together.  You will also receive a data dictionary.

_You must commit the downloaded csv files with your code into your repository._ There are too many ways to customize your query, and I am not giving any guidelines on what options you select beyond the date range listed above, so the graders will not be able to reproduce your data.

__The Task:__

You work in the education policy field, and you are proposing your organization use the Urban Institute data to study higher education.  Their nicely organized data offers a lot of opportunities to gain insights into the field.

The result of this project will be:
  1. One Jupyter notebook with all your code, plots, and writeup
  2. All data loading and merging code (but not downloading, which must use the Urban web interface)
  3. The creation of plots:
     - _At least 1_ static plot from MatPlotLib/Pandas/Seaborn.  This plot should be a "headline" result that you would, for example, embed in a writeup to your colleagues about why they should consider using this data.  Note that you will not be creating such a writeup - we're just framing the goal of our data visualizations. 
     - _At least 2_ interactive plots from Bokeh _(OR one plot with multiple panels, OR two related plots on one grid, etc)._  This plot should allow you and your colleagues to explore an assortment of interesting questions you could answer with this data.
     - Do not create more than 4 plots.  Two high-quality plots is greater than three or four average plots.

We have already had homework assignments in both MatPlotLib and Bokeh.  __I WANT you to go back to these earlier assignments and reuse functions you already created with this new data, to the extent possible.__  You will then include an approximately 10-20 line writeup in a Jupyter cell (change the type from Code to Markdown) about how well this worked for you.  

Did you identify problems in your earlier code (e.g. lack of functions, or functions that didn't generalise well)?  Did nothing you wrote before generalize to this new data very well?  Why not?  Were you able to copy one of your functions and use it with virtually no editing?  If so, why did that work so well?  Were you able to use part of a function?  If so, what did you have to change about it and is there a way you could have generalized it from the start?  And so on.

If you wrote your previous code well enough (and have a bit of luck), it's perfectly acceptable for you to copy nearly every line from your previous assignments.  Alternatively, if that doesn't work out then it's acceptable for every line of your new assignment to be new code.  In both cases you'll need to briefly explain what you found.  Also, if you do copy a function from a previous assignment, in whole or in part, please include a comment at the top of the function noting which assignment it came from.
