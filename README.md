# Police Use of Force

## The Task
The objective of this project was to analyze recently released data on police use of force in the state of California and identify potential areas for improvement regarding police conduct and police use of force policies.

## Background
The main dataset for this project comes from the California Department of Justice (DOJ) and Bayes Impact. Bayes Impact is a NGO based in San Francisco that uses data to solve some of "the world's biggest problems". In joint effort with the California DOJ, Bayes Impact built "a digital tool (URSUS) for the California DOJ that allows law enforcement agencies in California to digitally collect, track and report use of force that results in serious bodily injury or death." In 2016, all 800 California police departments were mandated to use the software. The recently released data for 2016 is now publicly available.

For more information on Bayes Impact and URSUS : https://www.bayesimpact.org/focus/justice

## Limitations
The main limitation of this data is the strict and narrow definition of "use of force". As mentioned above, agencies are only required to report data on "incidents that result in serious bodily injury or death of either the civilian or the officer and all incidents where there is a discharge of a firearm." In addition to that, very few Law Enforcement Agencies (LEAs) report data on things such as police officer trainings (i.e. the amount of training hours received or whether or not police officers received training on a given topic). Having data like this could give us insight into why we see specific trends or patterns in the data. 


## The Analysis
The analysis of the data was broken up by the following variables:
1. Race/Ethnicity
    - Officer
    - Civilian
    - Do they reflect the same race/ethnicity demographic as the state's?
1. Age
    - Officer
    - Civilian
1. Civilian Injury Level
    - Death
        - Race
        - Mental status
        - Perceived armed/not armed
    - Serious bodily injury
        - Race
        - Mental status
1. Geographic location:
    - Death cases
    - Serious bodily injury
    - Mental status cases
1. Logistic regression
    - Civilian: Death
        - What are the highest coefficients?
    - Civilian: Serious bodily injury
        - What are the highest coefficients?

## Findings

#### Race/Ethnicity

    - 

## Built With

- Jupyter notebook
- ScikitLearn
- Pandas

## Acknowledgments
- Gus Ostow
- Kevin Cho
