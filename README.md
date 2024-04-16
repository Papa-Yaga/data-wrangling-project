# data-wrangling-project
project_1_ironhack

## Titel:
## Carbon Footprint Quest: Navigating Emission and Fuel Trends

</details>

## Introduction

“Amidst a world where our planet struggles to breathe and individuals aspire for a better quality of life, the automotive industry stands as both a solution and a challenge. From corporations striving to deliver products efficiently to parents commuting to work or transporting their children, and from the hustle of daily travel to the complexities of public transport, vehicles play an integral role in our lives. However, this reliance on automobiles comes with its share of environmental consequences and sustainability concerns. As we navigate this intersection between necessity and impact, our project seeks to unravel the complexities of the vehicle market, shedding light on emissions, fuel consumption, and energy efficiency. By delving into data analytics, we aim to uncover insights that pave the way towards a more sustainable and promising future. Are we indeed on a path toward a better tomorrow?”

<br>

## Data Used
Car manufacture, car year, model of the car, car type, car price, storage and consumption of gas and/or energy, cars emission, gasoline price, and energy price.
- Challenges:
    - Duplicates
   - Format inconsistencies
   - Dynamic web content
- Solutions:
    - Standard structure and functions
    - Step by step web scan



<br>

## Project Question
- Are Eco-Conscious choices now pricier?
- Which manufacture is leading the charge in environmental stewardship?
   - Examining affordability efficiency emission and car offering
 
## Hypothesis
- Eco-conscious choices are not pricier compared to conventional options.
- At least one manufacturer stands out as a leader in environmental stewardship compared to others.


<br>

## Methodology
- Based on our hypothesis look for the needed data
- perceed to scrape the data
- once the data was scrape then cleaned it:
- Check for the coloumn which supposed to be category or numeric values, check the type and if it matchs, if not:
     - converted object into int for the coloumns which supposed to be numeric values. So that we carry out the coressponding operation
- Ensuring that our code does not corrupt the data while scraping it from the web

### Analysis
- Data exploration:
- Exploring the clean data set and undestand its structures and characteristics
- Identify the most relevant features for the analysis based on the potential impact of the outcome of the interest. Specifically for us:
     - Car manufacture,
     - Car year, model of the car,
     - Car type,
     - Car price,
     - Storage and consumption of gas and/or energy,
     - Cars emission,
     - Gasoline price, and
     - Energy price
 
###  Statistical Analysis
- Perform some operation with our variables i.e:
    - Enviromental impact = Emissions / Distance Traveled
 
###  Comparative Analysis
Our analysis involves comparing different manufacturers and car models to identify trends and variations in emissions, prices, efficiency, and other metrics. This allows us to assess which manufacturers are making the most significant contributions to environmental sustainability and offer the best value to consumers.

  <br>

## Visualisation

- Researched most common practices on visualisation in the industry to communicate the complex pattern in a clear and intuitive way.
- The technique we used are the following:
  - line graph
     - Effective for illustrating trends over time.
  - Scatter plot
     - To identify the relationship between the changes in different variables
     - (Car models and their difference taking into account the range and the car prices)
  - Histogram
    - Comparison between manufactures as seen the different emission, pricing strategies and the identification of outliers (unsual data)
    - Trend analysis. To analyse trend over time track the changes of emission level, pricing and eficiency over time and identify pattern.

  <br>

## Conclusion of the Analysis

- Gasoline cars, priced between $20,000-$60,000, generally show better total range performance, exceeding 600 miles, compared to electric cars in the same price range, which typically offer a maximum range of around 500 miles.
- Ford is a car manufacturer which offering the best prices. It has the lowest average emissions, while offering more cars to an average cheaper prices.



## Further Question:
- Considering factors beyond environmental impact and cost, what are the implications of electric vehicles compared to conventional cars on long-term maintenance costs, charging infrastructure availability, urban planning, and energy consumption?

 <br>

<br>

## Link to data sources and Notion:
- Energy and Gasoline Prices in the USA:
  - https://data.bls.gov/timeseries/APU000072610?amp%253bdata_tool=XGtable&output_view=data&include_graphs=true
  - https://data.bls.gov/timeseries/APU00007471A?amp%253bdata_tool=XGtable&output_view=data&include_graphs=true
- Cars and their information:
  - https://www.fueleconomy.gov/
- Notion:
  - https://www.notion.so/c02d94181ed74e17a1e965ce4058b84d?v=0c09bb811b0043a58ddbc1c60709523d&pvs=4
- Presentation Slides
  - https://docs.google.com/presentation/d/1QJZ1TYOyluKoP4VdChjbb0MAeCdvi5e6tpBYkk8Extg/edit?usp=sharing
  
<br>

  [Back to top](#faqs)

</details>
