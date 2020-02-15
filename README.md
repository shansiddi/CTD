# CTD
Shan Siddiqui<br />
Dr. Abadi<br />
B ME 450<br />
2/14/20<br />
<p align="center">
<b>CTD Project Link: https://github.com/shansiddi/CTD/blob/master/main.ipynb</b><br>
  
Access CTD project code by clicking link - open main.ipynb in Jupyter Notebook to run code which conducts data analysis. Data for project downloaded from Ocean Observatories Initiative (OOI). CTD is a conductivity, temperature, and pressure probe which dives into the ocean while taking measurements. OOI is an open source data-set which includes a vast library of CTD data. Data for this project came from the Oregon coast from Coastal Endurance and the Cabled Array. 24 hours worth of data was chosen for download as json files in Winter and Summer for each CTD available on the two observatories. For each profiler the number of dives, speed of sound profile for each dive, as well as average speed of sound profile were computed. 

Speed of sound was calculated with the following emperical relationship.
![](images/fig0.png)
<p align="center">
<b>figure 0: Speed of sound equation</b><br>

The data was plotted in various combinations to express the trends which answer the questions below. 

Problem 1: Compare the number of dives per day of the shallow profiler vs deep profiler
Answer 1: The shallow profiler generally ran 9 dives per day while the deep profiler would run 1 or 2. See Figure 1 for comparison of shallow and deep profiler daily operation.
![](images/fig1.png)
<p align="center">
<b>figure 1: Comparison between deep and shallow dives per day</b><br>
  
Problem 2: Where is the maximum value of ssp in each season? Explain why the max ssp should be there?
Answer 2: The maximum speed of sound in winter and Summer occured at the deepest part of the ocean a deep dive could go. Speed of Sound is a function of depth which increases as depth increases. So, as the CTD dove deeper speed of sound kept rising. See figure 2 for graph.
![](images/fig2.png)
<p align="center">
<b>figure 2: Maximum speed of sound Occurs at deepest ocean depths</b><br>

Problem 3: What is the effect on speed of sound of day vs night?
Answer 3: Daytime increases the temperature of the surface, in a rough sense the ideal gas equation would indicate that density would rise as a result of the increased temperature. Speed of sound does in fact increase during daytime, but this is only visible on the shallow profilers. The shallow profilers sit near the thermocline of the local region and are therefore impacted by surface effects. The deep profilers do not make surface effects evident. See figure 3 for comparison of deep and shallow profilers speed of sound vs time.
![](images/fig3.png)
<p align="center">
<b>figure 3: Speed of sound vs time, shallow profilers reveal effect of day vs night. Speed of sound increases during daytime somewhat. But the pattern can not be seen on a deep profiler as it is too deep of the thermocline to be in sight. Consequently shallow profiler sees spike at lowest depth during midday while deep profiler is consistent.</b><br>
  
  
  
References
NSF Ocean Observatories Initiative Data Portal, http://ooinet.oceanobservatories.org. Downloaded on (2/14/20).
