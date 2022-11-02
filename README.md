# Flight-Performance-Delay-Dashboard-Project

Dash- as a python framework is used to build interactive web application to enrich experience of data visualization. In this project, I will explain how to create a dash application to present an interactive report. The aim of this project is to create an interactive visualization to monitor and report US domestic airline flights performance. This visualization can be used to support decisions to improve flight the reliability thereby increasing customer reliability.

There are two report keys in this project, range in the span of 15 years from 2005 to 2020. The Yearly Airline Performance Report consists of five charts as follows :

- Number of flights under different cancellation categories in bar chart.
- Average flight time by reporting airline in line chart.
- Percentage of diverted airport landings per reporting airline in pie chart.
- Number of flights flying from each state in choropleth map.
- Number of flights flying to each state from each reporting airline in treemap chart.

Meanwhile, Yearly Average Flight Delays Statistics will provide five line charts that illustrate the average of delay by reporting airline per year caused by : carrier, weather, national air system (NAS), security and late aircraft. The outline of the visualization will look like this :
![image](https://user-images.githubusercontent.com/47457939/199481918-267763d1-9b58-4cfc-a989-3ba0172f02b1.png)

This visualization will contain two dropdown menus for choosing report type and year. Each dropdown will be designed with two inner divisions, one containing information about the dropdown and the dropdown itself. The graphs will be shown below the dropdown and to create them I will use callback function to compute the data, create graph and return the layout.

# Yearly Airline Performance :

![image](https://user-images.githubusercontent.com/47457939/199482349-a050dd5b-5221-4bb0-8e64-793499f6a4c9.png)
![image](https://user-images.githubusercontent.com/47457939/199482389-1e42dc08-cb7a-4506-b42e-8dd1b5eaf0a5.png)

# Yearly Flight Delays Statistics :
![image](https://user-images.githubusercontent.com/47457939/199482491-627b1145-6f74-4b5c-9416-3eec80c6677e.png)
![image](https://user-images.githubusercontent.com/47457939/199482539-1fb48669-abe1-4078-86bb-c5440b8577a0.png)


# Feel free to fork and Improve it in your own unique way.
Stay Curious.

Written by Darklight-Ismail.
