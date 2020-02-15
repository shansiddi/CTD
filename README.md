# CTD
Shan Siddiqui<br />
Dr. Abadi<br />
B ME 450<br />
2/14/20<br />
<p align="center">
<b>CTD Project Link: https://github.com/shansiddi/CTD/blob/master/main.ipynb</b><br>
  
Access CTD project code by clicking link - open main.ipynb in Jupyter Notebook to run code which conducts data analysis. Data for project downloaded from Ocean Observatories Initiative (OOI). CTD is a conductivity, temperature, and pressure probe which dives into the ocean while taking measurements. OOI is an open source data-set which includes a vast library of CTD data. Data for this project came from the Oregon coast from Coastal Endurance and the Cabled Array. 24 hours worth of data was chosen for download as csv files in Winter and Summer for each CTD available on the two observatories. For each profiler the number of dives, speed of sound profile for each dive, as well as average speed of sound profile were computed. 

Plotting number of dives per day for shallow and deep profilers revealed that fewer dives are conducted on a given day for deep profilers. Fewer deep dives are advisable to protect equipment from great stresses as well as to keep costs low. CTD data is generally expensive deep dives even more so than shallow ones. See figure 2 for comparison between deep and shallow dives per day.
![](images/fig2.png)
<p align="center">
<b>figure 1: Comparison Between Deep and Shallow Dives Per Day</b><br>
  
The greatest speed of sound values hit about 1550 m/s usually occuring at great depths of the ocean in the Winter time. However in the Summer the effect of temperature is much more noticeable bumping speed of sound up to 1500 m/s. Speed of sound is a function of depth, temperature, and salinity. Empirical relations for the speed of sound in the ocean reveal that temperature has the greatest effect of the value. See figure 2 for the top speeds of sound.
![](images/fig3.png)
<p align="center">
<b>figure 2: Top Speeds of Sound</b><br>
The speed of sound being a function of temperature would imply that daytime data would vary from night time data. However, the OOI data tested did not reveal trends in the speed of sound profile based on time of day. See figure 3 for the null effect of daytime versus night time. Further analysis ought to be conducted particularly near the surface to find trends which show the day time effect. Theoretically speed of sound ought to increase during daytime with rising temperature consequently increasing the rapid change in speed of sound profile as depth is reached.

![](images/fig4.png)
<p align="center">
<b>figure 3: No Effect on Speed of Sound daytime versus nighttime</b><br>
  
Surface water temperatures during winter time are significantly lower than during summer. As a result speed of sound at the surface is much less during the winter versus the summer. Consequently the rapid change in speed of sound as depth is reached becomes much greater in the summer months following the thermocline. See figure 4 for a side by side comparison of the seasonal effect. 


![](images/fig5.png)
<p align="center">
<b>figure 4: Seasonal Effect on Speed of Sound</b><br>
  
The cabled array further out in the ocean from shore compared to coastal endurance presents a more pronounced thermocline. See Figure 5 for the comparison between the arrays. A more pronounced thermocline is a result of greater surface temperature, it is likely that closer to the shore waves carry heat away from the CTD faster than in the mid ocean in this case. However a general trend can not be drawn from these two data points, the spatial depencdence of the speed of sound profile ought to be studied in greater detail. 


![](images/fig6.png)
<p align="center">
<b>figure 5: Location Effect on Speed of Sound</b><br>
  
References
NSF Ocean Observatories Initiative Data Portal, http://ooinet.oceanobservatories.org. Downloaded on (2/14/20).
