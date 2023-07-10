# Airline Delay Analysis

![A screenshot of your application. Could be a GIF.](Screenshot1.png)


## Project Goals

In this project, our aim was to explore the Airline Delay Dataset available on the Federal Aviation Administration Website (https://www.faa.gov/data_research) through Exploratory Data Analysis. We believe this exploration gives a user an idea about the delays across major airports in the United States (30) for 17 Airline Carriers. This exploration might be useful for them to understand expected average delay times if the reason for the delay is known. It can also help the user identify and factor in delays while planning their trips, whether it be a vacation or a work trip. The fetched dataset was a clean subset of the airline data available on the website. Our dataset of 4412 data points from November 2021 to November 2022 records the following features: 
year: 2021, 2022
month: January to December
carrier: Airline carrier code
carrier_name: airline carrier name
airport: airport code
airport_name: airport name
arr_flights - total count of flights
arr_del15 - total count of delayed flights
carrier_ct: count of flights delayed to carrier issues
weather_ct: count of flights delayed to weather issues
nas_ct: count of flights delayed to National Aviation System issues
security_ct: count of flights delayed to security reasons
late_aircraft_ct: count of flights delayed to aircraft arriving late issues
arr_delay = total delay minutes for arr_delay flights
carrier_delay - minutes delayed due to carrier issues
weather_delay - minutes delayed due to weather-related reasons
nas_delay - minutes delayed due to Nation Aviation System Delay
security_delay - minutes delayed due to security reasons
late_aircraft_delay - minutes delayed due to aircraft arriving late from a previous flight

## Design

First, we wanted to help the user determine airline delay. Additionally, we enjoyed the application being interactive so we provided filters of airline, airport, causes, and month based on which users can view different results. We plotted to scatter plots to visualize the distribution of data and a geographical scatter plot showing the busiest airports to provide an informative visualization for the user. We did consider using a bar plot and line plot, however, we found scatter plots to be the most useful, providing users with better visibility, more interaction, and context. 

## Development

Our team split the work into two main components. One team member focused on developing the filterable graphs, while the other focused on creating the geographical scatter plot. The development process involved brainstorming ideas, prototyping, and testing different approaches to ensure that the final product was functional and visually appealing. In terms of the time spent developing the application, we estimate that we spent approximately 24 people-hours in total.The most time-consuming aspect of the project was create the geographical scatter plot, including using an API to obtain the latitude and longitude of each airport. However, we worked collaboratively to overcome any challenges and ensure that the final product met.

## Success Story

Our project addresses the goal of the project of providing the user with information about delay times across airports and airlines. American Airlines has had the highest delays over the past year, closely followed by SouthWest Airlines and Delta. Clearly, anyone flying via these flights should be aware of the delays they may experience. Passengers flying in and out of any of Chicago O’Hare International, Dallas/Fort Worth International Airport, Hartsfield-Jackson Atlanta International Airport or Denver International Airport can also expect high delays. 
A personal success story for this project was the accomplishment of building an interactive web application for the visual exploration of data and learning a new tool to achieve the same. 


Team members: tarushig@andrew.cmu.edu and sjethmal@andrew.cmu.edu
Online URL: https://cmu-ids-spring-2023-assignment-3-airline-delay.streamlit.app/

