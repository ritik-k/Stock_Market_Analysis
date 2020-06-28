# Decline in stock value of BEACH companies due to the coronavirus pandemic (COVID-19)

### Why analyse BEACH stocks?
### The ‘BEACH’ Stocks (Booking, Entertainment and Live Events, Airlines, Cruise and Casino, Hotel and resort) have been hit the hardest due to the economic downturn caused by COVID-19. The COVID-19 outbreak has turned the econmoy upside down, the BEACH stocks have seen more tham $332B in value evaporate during the months of Feb-Mar 2020. In this project we look at the the steep losses across companies in different sectors. The stocks are considered from 1 Jan 2020 - 31 April 2020. Analysis is done primarily on values from 19 February 2020 - 23 March 2020. Data has been accessed from [Yahoo Finance](https://in.finance.yahoo.com/) using pandas_datareader library.

### Based on the data, these were the main questions I focused on answering:
1. What is the decline in stock values of different companies across various sectors?
2. What is the decline in stock values of S&P BSE SENSEX and NIFTY 50?
3. Visualising percent decline of stock values of different companies using a horizontal bar plot.

## Code and Resources Used

### Python Version : 3.8.2
### Libraries Used : pandas, numpy, matplotlib, seaborn, plotly, cufflinks, chart_studio, pandas_datareader
### Dataset : [Yahoo Finance](https://in.finance.yahoo.com/)

## P.S - To access the interactive version of the plots, please checkout the link mentioned at the bottom of this page.

# Visualisations

### 1. Booking Industry
### Companies - Booking Holdings, Expedia Group, Allegiant Travel
![Booking Industry](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/gifs/booking.gif)
#### The effect of the outbreak on various travel bookings brands have been severe. Booking Holdings, the parent company to Booking.com, Priceline, Kayak and OpenTable, witnessed share price declines of over 40% since the peak. Expedia Group has been affected the worst with a decline of 58%. Online ticket booking platform BookMyShow has laid off or furloughed 270 employees as it expects its revenue to be "greatly reduced" in the coming months, hit by the COVID-19 pandemic and lockdown.
### [Static Image](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/images/booking.png)

### 2. Entertainment Industry
### Companies - Live Nation, Six Flags, Cedar Fair, The Walt Disney Co, Penn National Gaming
![Entertainment Industry](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/gifs/entertainment.gif)
#### Ticket sales for concerts, movies, and other events are falling across the entertainment industry,  precipitously due to cancellations or postponements of sports events and festivals. Walt Disney Co, despite having a wide array of investments and holdings had suffered a 39% decline. Walt Disney has estimated that global measures to contain the coronavirus pandemic has cut down the company's profits by USD 1.4B, mostly from its shuttered theme parks.
### [Static Image](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/images/entertainment.png)

### 3. Air Travel Industry
### Companies - Delta Air Lines, United Airlines, American Airlines, Southwest Airlines, Alaska Air Group, Air Canada
![Airline Industry](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/gifs/airlines.gif)
#### As the COVID-19 outbreak has spread to over 200+ countries, many governments have implemented sweeping travel restrictions, which has paralysed the Air Travel industry. The global airline industry —which employs over 10M people— supports $2.7T in global economic activity across an average of 12M passengers per day. The worldwide airline revenue is estimated to fall by as much as USD 113B in 2020. This will have a marked effect on the broader economy. The ripple effect can be seen in the Oil industry as in Q2 2020, global oil consumption is projected to fall by 25M barrels per day.
### [Static Image](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/images/airlines.png)

### 4. Cruise and Casino Industry
### Companies - Carnival, Royal Caribbean Cruises, Norwegian Cruise Lines, Las Vegas Sands, MGM Resorts International, Wynn Resorts, Caesars Entertainment, Eldorado Resorts
![Cruise and Casino Industry](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/gifs/cruise.gif)
#### For the cruise line industry, global operations came to a 30-day standstill in mid-March. Royal Caribbean Cruises, has seen its market cap plummet almost 74%. The influence of the cruise industry is far reaching. Many small island nations (especially in the Caribbean) rely heavily on the jobs and cash flow that ships provide.
### [Static Image](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/images/cruise.png)

### 5. Hotel and Resorts Industry
### Companies - Marriott International, Hilton, Hyatt Hotels, Choice Hotels International, Wyndham Hotels & Resorts, Park Hotels, Vail Resorts, Marriott Vacations Worldwide
![Hotel and Resort Industry](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/gifs/hotel.gif)
#### Governments across the world have sealed international borders; there is a suspension of all international and domestic flights; compounded by a nationwide lockdown, together this is bound to bring an unprecedented phase in the history of the hospitality industry. Baird/STR Hotel Stock Index is a benchmark for the hotel sector’s overall health. On 19 February 2020 the index stood at 4983 while on 24 March 2020 it was 2439, which is a 51.05 % decline, this sums up the condition of the hotel industry.
### [Static Image](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/images/hotel.png)

### Visualising percent decline of all companies
![Percent decline of all companies](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/gifs/barh.gif)
#### International Monetary Fund (IMF) says that the global economy will shrink by 3% in 2020. The IMF described the decline as the worst since the Great Depression of the 1930s, it said that the coronavirus has plunged the world into a "crisis like no other".
### [Static Image](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/images/bar-h.png)

### In our own backyard - SENSEX AND NIFTY
### The plot is created using a dropdown for better visualisation.
![Sensex and nifty](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/gifs/india.gif)
#### Benchmark indices Sensex and Nifty which were going strong despite weak GDP growth since the beginning of this year fell victim to the coronavirus outbreak across the world. Sensex witnessed it's second-biggest fall (in terms of points) in a single day.
### [Static Image](https://raw.githubusercontent.com/ritik-k/Stock_Market_Analysis/master/images/india.png)

## Usage and Interactive plots:
#### This project is best viewed in a notebook viewer, which can be accessed [here](https://nbviewer.jupyter.org/github/ritik-k/Stock_Market_Analysis/blob/master/Stock_Market_Analysis.ipynb). In this notebook, you will find a walk through of the work done, interactive plots and the respective code.
