# PyPymaceuticals
<img src="/Images/Laboratory.jpg" width="1080">

By Vivianti Santosa

The first observation that I want to report is that I notice on the contrary of what was stated in the introduction, there were actually 250 mice in the study, however one set of data for a mice that is part of the Stelasyn study got messed up with the one from Propriva. Because there is no way I would know which mouse belongs to which study, I decided to drop both. <br>

The summary statistics for the tumor volume are as follow :<br>
<img src="/Images/Table1.png" width="360">

We are asked to create a bar chart, to show the number of mice that survive the study. From the guidance of our instructor, here is the chart that is being expected by the report :<br>
<img src="/Images/Bar2.png" width="600">

However in my opinion, the above chart is not a good representation for the information because the total number of mice observed here is the total of the number of the same mice being observed at different times. <br>
For each treatment we have max 25 mice that die along the study, and thus the number decreases on each observation, and thus the number here is not a real number. The chart that I am presenting in the next page, though crowded, is a better representation of the data.<br>
<img src="/Images/Bar4.png" width="900">

In this chart we can see clearly that over the time more mice from Capomulini and Ramicane survived the study. <br>

However, since this is actually a time base data, line graphs like in below are the more appropriate charts to showcase the information.<br>
<img src="/Images/Bar7.png" width="360"> <br>

The next chart that is a pie chart that shows that there both gender is approximately equally represented in this study.<br>
<img src="/Images/Pie2.png" width="480">

As being requested, I evaluate for potential outliers, both from quantitative method and from boxplot. Instead of only focusing on the drug regiments of interest, I evaluated the whole study. The result is as follow :<br>
<img src="/Images/Plot1.png" width="720"><br>
<img src="/Images/Table2.png" width="650">

As can be seen here, most of the result of the study is within the range. There is only one incident of outlier in Infubinol. 
It can also be observed here clearly that Capomulini and Ramicane are the only drugs that reduce the size of the tumors. 
From the data of the overall study we chose the data and created a boxplot chart of the four drug regimens  of interest. Here we can also see that Capomilin and Ramicane are superior to Ceftamin and Infubinol.<br>
<img src="/Images/Plot2.png" width="680">

Within the study of Capomulin, mice experience reduction and enlargement size of tumor as can be seen in the sample graph (of one mouse) and overall graph of the tumor volume over study time
<img src="/Line1.png" width="480"><br>
<img src="/Images/Line3.png" width="480">    <img src="/Images/Line2.png" width="480">

The last study is about the correlation between the mouse weight and the size of the tumors.The correlation coefficient is 0.84, which means that there is a strong relation between the size of tumors and the weight of the mouse. The slope is 0.95, which means there is a positive relation between the mice weights and the size of the tumors. <br>
<img src="/Images/Scatter3.png" width="600">

In conclusion, the drug Capomulin clearly has positive results as can be seen as the least number of mice dying as well as the reduction size of tumor, as can be seen in the average tumor size and the tumor size at the end of the study. Although it is not conclusive if it is superior to Ramicane, which produces slightly better results, although it lost one more mouse by the end of the study period.<br>

<img src="/Images/Table3.png" width="280">    <img src="/Images/Bar6.png" width="400"><br>
                
As for the learning point of MatPlotLib - Various charts that I can create in Matplotlib and Pandas enable my audiences to see data more clearly and help them in decision making. However the right data and the right type of charts need to be chosen to represent data in meaningful ways and to highlight the points that we want to show. <br>

