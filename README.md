# stop_and_frisk
NYC's Stop-and-Frisk policy in action
This is my submission for the Lede Program for Data Journalism's second assignment. 

New York City's stop-and-frisk policy, where police officers can stop and search any person for a weapon based on "resonable suspicion" was deemed unconstituional in 2013 after critics claimed the practice led to racial profiling of Black and Latino men. 

The policy still exists today and the New York Police Department discloses data about each time they stop and frisk an individual. I analyzed  this data from 2023 to see if Black and Latino men are disproportionately stopped and frisked a decade after the practice was deemed unconstitutional. 

I took publicly available data about the number of stop-and-frisks conducted in each precinct in New York City and analyzed it in Pandas to see the number of people stopped and frisked in each precinct. I then filtered and downloaded data about the racial demographics of New York City from the Census Bureau's American Community Survey. 

I visualized the data in QGIS and customized a map illustrating the number of stop and frisks by precinct in Illustrator. Finally, I made a scrolly telling story to add annotations to the map about the racial demographics of each precinct based on census data. 

My analysis showed that the precincts with the most stop and frisks were predominantly Hispanic and African American and that NYPD police officers percieved the majority of people they were stopping and frisking as Black and Hispanic. 

The two datasets I used for the analysis can be found here: 
https://data.cityofnewyork.us/Public-Safety/The-Stop-Question-and-Frisk-Data/ftxv-d5ix/about_data
https://data.census.gov/table?q=race&t=Race%20and%20Ethnicity&g=050XX00US36005$1500000,36047$1500000,36061$1500000,36081$1500000,36085$1500000&y=2021

## What I learned
I had more practice analyzing a dataset in pandas. The most challenging part of this project was visualizing the data. I spent a lot of time using QGIS to make an accurate map. The data from the Census bureau was very complicated and took me a long time to filter. I also learned how to make a scrollytelling website, I spent a lot of time trying to use AI to HTML, but was unable to trigger annotations at the time I wanted them to trigger, so I ended up using a scrollytelling template with images to add interactive annotations to my map. 

## Things I would have liked to do
I would have liked to visual represent race on my map, but I ended up only using the number of stop and frisks in each precinct. The data included the race of each individual, but my mentor said it would be inaccurate to display data about the race of individualds that the NYPD recorded if I didn't know exacltly how they were recording that race, including if the data was how police officers percieved race or how the people who were stopped and frisked self-identfied. For this reason, I relied on racial demographics of census blocks to make analysis about race in the New York precincts. But the census data was challenging to work with and I didn't have enough time to visualize it in a way that was easy to understand. 
