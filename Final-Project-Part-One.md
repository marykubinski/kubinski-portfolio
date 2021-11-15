# Final Project Part One
## Fatal Encounters: Addressing the disparities and violence in US traffic stops  

## Outline

Traffic stops are the most common way that police interact with the public in the United States. Police pull over more than 50,000 drivers on a typical day, more than 20 million motorists every year (The Stanford Open Policing Project). Recent reporting by the New York Times found that throughout the United States, police consider traffic stops to be among the most dangerous things they do. Yet, an investigation of traffic stop data reveals that this perception of risk is significantly overstated. While not statistically supported, the belief has an impact on police department and courtroom culture and standards, which not only creates a risk to the public but continues a standard allowing impunity for the majority of police officers who use lethal force at vehicle stops.

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
   - Police survey data 
- What do experts recommend? 
   - Message: Civilian deaths and costs to community could be avoided if police officers do not put themselves in danger/have better training. 

### Part 4: Call to Action 
- Ongoing efforts to use open data/political participation to call for change at local/state/federal level
   - Link to an low-level petition for officer training 
   - Provide higher-level action about separating traffic stops from municipal funding 

## Sketches

## Data
The following data sources have been collected and aggregated by the The Washington Post, and the research groups Mapping Police Violence. A blog post from the RAND corporation validated and referenced the Police1 survey. 

1. [Police Scorecard](scorecard.csv) by the Police Scorecard Project 
2. [Fatal Police Shootings](fatal-police-shootings-data.csv) by the Washington Post 
3. [Contacts Between Police and the Public](DOJ_police_contacts.pdf) by the DOJ Bureau of Justice Statistics
4. [Police Perceptions Survey](Police1_Survey.pdf) by Police1 
 
The Police Scorecard is a public evaluation of policing, tracking levels of police violence, accountability, racial bias and other policing outcomes for over 16,000 municipal and county law enforcement agencies. I plan to use this dataset to evaluate trends in how...  The Fatal Police Shootings dataset contains individual datapoints for every fatal shooting  by a police officer in the line of duty since Jan. 1, 2015. I plan to use this disaggregated data to create a map. After aggregating the Fatal Police Shootings, I plan to show... The DOJ record of Contacts Between Police and the Public was most recently updated in 2018 and it can be used in the introduction of police-public interactions. The Police Perceptions Survey was a 29-question survey, completed by 1,036 police officers in Spring 2021. Survey content includes the responses on common non-compliance behaviors, traffic stop training frequency and methods, and departmental policies. I plan to use these data in the resolution section to demonstrate the gaps and opportunities for improvement that police officers have identified and reported.  

## Method and Medium 

I plan to complete the final deliverable for my project using Shorthand. Some of the essential visuals will be charts showing... 

My first step will be to review, clean, and aggregate data. The fatal police shooting and police scorecard are disaggregated to the individual incidence level. 

At this time, I plan to  build some charts using Tableau, Flourish, and possible ggplot in R. I intend to build as many as I can with Tableau, since one of my goals in this course is to become more familiar with Tableau. I plan to make one or two maps for the project and feel confident this can be done in Tableau, following the class tutorial. I have found Flourish to be more intuitive, especially for interactive charts and graphs. I may decide to switch to R/ggplot if I encounter challenges working with large datasets. 
