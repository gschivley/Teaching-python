# Pandas
To download the data files:  

1. EIA 923: click [this link](https://github.com/gschivley/Teaching-python/blob/master/Pandas/EIA923_Schedules_2_3_4_5_M_10_2016.xlsx?raw=true)
2. EIA 860 (may_generator2016): click [this link](https://github.com/gschivley/Teaching-python/blob/master/Pandas/may_generator2016.xlsx?raw=true)
3. EPA emissions: right-click [this link](https://github.com/gschivley/Teaching-python/blob/master/Pandas/EPA%20emissions.txt?raw=true) and select "Save link as"

## What are the different files in this folder?
Aside from the three data files and two output files ("Final data.csv" and "Final_monday.csv"), there are three .ipynb notebook files.
- [A pre-written notebook](http://nbviewer.jupyter.org/github/gschivley/Teaching-python/blob/master/Pandas/Pre-written%20Pandas%20example.ipynb) that I used as reference when live-coding in each of the two sessions. This has a slightly more complicated section where monthly data columns in EIA 923 are stacked, which I ended up skipping over.
- [The notebook from Friday's session](http://nbviewer.jupyter.org/github/gschivley/Teaching-python/blob/master/Pandas/Live%20coded%20notebook%20%28Friday%29.ipynb). This is exactly what you see created in the [YouTube video from Friday](https://youtu.be/Uuzc2iRupa0).
- [The notebook from Monday's session](http://nbviewer.jupyter.org/github/gschivley/Teaching-python/blob/master/Pandas/Live%20coded%20notebook%20%28Monday%29.ipynb), which covered the exact same material as the session on Friday. There were a few different questions that came up, so it might be worth watching through the material a second time ([YouTube video available here](https://youtu.be/Jy6dc62jJrc)), especially if you are new to Pandas.

## Where to go for more resources
I gave a quick walkthough of loading and manipulating some data. You'll probably want to learn more and better understand how to efficiently use Pandas in your own workflow. Check out these resources:
- Kevin Markham has a great [series of short videos](http://www.dataschool.io/easier-data-analysis-with-pandas/) that is designed for people who have never used Pandas. A special shout-out to his [walkthrough](https://youtu.be/4R4WsDJ-KVc?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) of `SettingWithCopyWarning`, which I didn't do a great job explaining in my sessions.
- Once you get through Kevin's videos, be sure to take a look at Tom Augspurger's [Modern Pandas series](https://tomaugspurger.github.io/modern-1.html). I didn't read his section on [Fast Pandas](https://tomaugspurger.github.io/modern-4-performance.html) until after these sessions were recorded. Using `.apply(..., axis=1)` is quite slow and should be replaced with functions that take arrays as inputs and perform vectorized operations.
- Although it covers more than Pandas, be sure to check out Jake VanderPlas' [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook). It's also a great place to learn more about numpy and machine learning.
