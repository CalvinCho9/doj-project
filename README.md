# doj-project
Conducted as part of the 2024 United States Department of Justice Student Research Expo Program. 
Link to presentation: https://bjs.ojp.gov/events/bjs-student-research-expo

Investigation of Forensic Crime Lab Characteristics and their Impact on Competency Testing Results

The Census of Publicly Funded Forensic Crime Laboratories, 2020 (ICPSR 38901) provides data on forensic crime laboratories from four jurisdictions: federal, state, county, and municipal. In a 2023 study, Connor Brooks utilized this dataset and shocacased a trend where a lab’s competency testing results differed significantly depending on what jurisdiction it was under: labs under federal jurisdiction were rated on average 93.9% for competency testing while state, county, and municipal labs were rated at 91.3%, 85.5%, and 77.4% respectively.

My immediate hypothesis was that since the majority of crime labs received funding through federal grants (72%), federal labs likely received a greater budget. However, when dividing the total budget per jurisdiction type by number of cases received per jurisdiction, it revealed that federal labs have the highest funds per case ($920), state, county, and municipal labs are funded $610, $685, and $760 per case. This contradicted the competency ratings as municipal labs were funded only second to federal labs per case but had the lowest competency rating. Thus, while the budget may have an underlying role and influence competency of these labs, there are clearly other variables that must be playing an influential role.  

To determine the influence of a lab’s characteristics on competency testing results, my plan is to run a multiple linear regression analysis on models with budget allocation, number of employees, number of cases, and types of requested cases variables to assess what could be driving the different levels of competency levels. 
