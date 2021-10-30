# Matplotlib

![Matplotlib](https://github.com/Amanyxdav/Matplotlib/blob/main/matplotlib.png)

Matplotlib is a python library used for Data Visualization. You can create bar-plots, scatter-plots, histograms and a lot more with matplotlib.

Data Visualization is an essential component of a Data Scientist’s skill set. It is extremely necessary to show the insights found from the analysis of the data in the form of beautiful, aesthetic graphs and this is where matplotlib comes to our rescue.

Here are some graphs which have been implemented by using matplotlib:

#### * Pie Chart:
With these two lines of code we are able to create a pie-chart that shows us the distribution of different fruits.

```python
plt.pie(quantity, labels = fruit, autopct'%0.1f%%'
        ,colours=['yellow', 'grey', 'blue', 'black'])
        
plt.show
```

![Pie Chart](https://github.com/Amanyxdav/Matplotlib/blob/main/pie_chart_1.png)

#### * Bar-Chart:
Here we are creating a bar-chart using a dictionary. The ‘keys’ of dictionary are stored in ‘names’ and the ‘values’ are stored separately. Then, using plt.bar() method, we map the names onto the x-axis and scores of the students onto the y-axis.

```python
student = {"Bob":87,"Matt":56,"Sam":27} 
names = list(student.keys()) 
values = list(student.values()) 
plt.bar(names,values) 
plt.title("Bar Plot") 
plt.xlabel("Names") 
plt.ylabel("Marks") 
plt.grid(True)
```

![Bar Chart](https://github.com/Amanyxdav/Matplotlib/blob/main/bar_chart.png)

These were just a few graphs with matplotlib. Using this library, you can make box-plots, scatter-plots, doughnut charts, heatmaps and a lot more.
