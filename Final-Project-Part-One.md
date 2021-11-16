# Final Project Part One
## Fatal Encounters: Addressing the disparities and violence in US traffic stops  

## Outline

Traffic stops are the most common way that police interact with the public in the United States. On the average day, police pull over more than 50,000 drivers, which amounts to more than 20 million motorists every year (The Stanford Open Policing Project, 2021). Recent reporting by the New York Times found that throughout the United States, police consider traffic stops to be among the most dangerous things they do (Levenson, 2021). Yet, an investigation of traffic stop data reveals that this perception of risk is significantly overstated. While the data tells a different story about the risks associated with traffic stops, this popular perception has an impact on police department and courtroom cultures and standards. Beliefs, practices, and lack of consequences surrounding police actions during traffic stops not only create more dangerous situations for the public but continues a trend of impunity for the majority of police officers who use lethal force at vehicle stops.

### Part 1 : Setup 
- Introduce traffic stops 
   - What is the goal of traffic stops?
   - What is funded by traffic stops? 
- Introduce police-public Interactions
   - Unequal Demographics by race/gender
- High- level Problem with police violence 
   - Show map 
   - Proportion of police violence that is related to traffic stops 

### Part 2: Conflict 
- How often is deadly force at a traffic stop because of danger to the police?
   - Statistics show police are in danger very infrequently during traffic stops 
   - Statistics show police create a more dangerous situation by not following procedures 
   - Statistics show impact on communities are unequal 
- Where is this happening and how are police trained? 
   - Statistics from the police scorecard dataset 
- Who is accountable when police take lives? 
   - Frequency of convictions vs. settlement payouts 

### Part 3: Resolution 
- What do police say? 
   - Police survey data shows trends in data about procedure, training, and experience with non-complient drivers
- What do experts recommend? 
   - Message: Civilian deaths and costs to community could be avoided if police officers do not put themselves in danger/have better training. 
   - The role of ticket revenue and other streams of funding 

### Part 4: Call to Action 
- Ongoing efforts to use open data/political participation to call for change at local/state/federal level
   - Link to an low-level petition for officer training 
   - Provide higher-level action about separating traffic stops from municipal funding 

## Sketches

## Data
The following data sources have been collected by the The Washington Post, and the research groups Mapping Police Violence, as well as the Department of Justice and the Police1 research team. The RAND corporation blog validated and referenced the Police1 survey. 

1. [Police Scorecard](scorecard.csv) by the Police Scorecard Project 
2. [Fatal Police Shootings](fatal-police-shootings-data.csv) by the Washington Post 
3. [Contacts Between Police and the Public](DOJ_police_contacts.pdf) by the DOJ Bureau of Justice Statistics
4. [Police Perceptions Survey](Police1_Survey.pdf) by Police1 
 
The Police Scorecard is a public evaluation of policing, tracking levels of police violence, accountability, racial bias and other policing outcomes for over 16,000 municipal and county law enforcement agencies. I plan to use this dataset to evaluate trends in how policing differs depending on location, which is impacted by funding and racial and ethnic makeup of the community. Trends in the data exist that show some police departments, which have low totals in the Scorecard, have high occurances of violence and police killing year after year. The Fatal Police Shootings dataset contains individual datapoints for every fatal shooting  by a police officer in the line of duty since Jan. 1, 2015. If I am able to separate shootings including a traffic stop, I plan to use this disaggregated data to create a map. The DOJ record of Contacts Between Police and the Public was most recently updated in 2018 and it can be used in the introduction of police-public interactions. I plan to use this data to establish the frequency of public-police interactions and what proportion of interactions are traffic stops. Finally, the Police Perceptions Survey was a 29-question survey, completed by 1,036 police officers in Spring 2021. Survey content includes the responses on common non-compliance behaviors, traffic stop training frequency and methods, and departmental policies. I plan to use these data in the resolution section to demonstrate the gaps and opportunities for improvement that police officers have identified and reported.  

## Method and Medium 

I plan to complete the final deliverable for my project using Shorthand. This will be my first experience using Shorthand, but I believe the in-class demonstration will be a helpful starting point. In addition to the charts mentioned in the above outline and sketches, I plan to incorporate call out statistics, key quotes, and images. Policing and police training, as a sensitive and highly-debated issue in policy and local politics, has powerful images that I hope to find on Unsplash. I plan to hold colors constant throughout the presentation that match the mood of the serious topic, but still allow for key data points to be highlighted.   

My first step will be to review, clean, and aggregate data. The fatal police shooting and police scorecard are disaggregated to the individual incidence level. This disaggregated data will be applicable to maps with point and gradient features. However, to create summary statistics that are easily interpreted in a chart, I anticipate a need to clean data and create additional categorical variables of interest for grouping. Additionally, the Police1 survey and DOJ report are both available only in PDF format. For the DOJ document, I plan to use Tabula to extract the tables. For the survey, only already visualized data is available, so I will need to create spreadsheets of the results by hand.

At this time, I plan to  build some charts using Tableau, Flourish, and possible ggplot in R. I intend to build as many as I can with Tableau, since one of my goals in this course is to become more familiar with Tableau. I plan to make one or two maps for the project and feel confident this can be done in Tableau, following the class tutorial. I have found Flourish to be more intuitive, especially for interactive charts and graphs. I may also decide to switch to R/ggplot if I encounter challenges working with large datasets. 

## Sources

"Findings." The Stanford Open Policing Project. Accessed November 15, 2021. https://openpolicing.stanford.edu/findings/

Levenson, Michael. “Pulled over: What to Know about Deadly Police Traffic Stops.” The New York Times. The New York Times, October 31, 2021. https://www.nytimes.com/2021/10/31/us/police-killings-traffic-stops-takeaways.html. 
