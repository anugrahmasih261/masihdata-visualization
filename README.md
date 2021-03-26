# masihdata-visualization
this is remind me where i started as data scientist and it's amazing
import matplotlib.pyplot as plt
#take emp ids and salaries for sales dep
x=[1001,1002,1003,1004,1005,1006]
y=[10000.20,20000.23,300000.00,40000.25,50000.50,600000.25]
#take emp ids and salaries for production dept
x1=[1007,1008,1009,1010,1011,1012]
y1=[50000.50,60000.023,7000.25,8000.33,99000.00,1000000.00]
#create bar graph
plt.bar(x,y, label='sales dept',color='red')
plt.bar(x1,y1, label='production dept',color='green')
#set the labels and legend
#we use legend() when different sets of data is ploted to have diff colors of lebels
plt.xlabel('empi d')  #this is on axis we are writing on x axis and y axis
plt.ylabel('salaries')
plt.title(' MASIH PVT LTD')
plt.legend()
plt.show()  #it is udes to display bar graph

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

