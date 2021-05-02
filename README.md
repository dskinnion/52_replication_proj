# GOV 52: Replication Project

My name is Dominic Skinnion, and I am a current Sophomore at Harvard College studying Government and Statistics. If you would like to reach me, my email is dskinnion@college.harvard.edu.

This project was completed for GOV 52: Models, taught by Professor Gill at Harvard University. I have chosen to replicate the paper "Leader Age, Death, and Political Liberalization in Dictatorships" by Professor Sarah Hummel of Harvard University.

I have been interested in authoritarian regimes, and I have had the honor of taking GOV 1249: Authoritarianism with Professor Hummel at Harvard University in the Spring of 2021. My sincerest thanks to Professor Hummel for her instruction and for making her code and materials open to the public through the Harvard Dataverse.

## Original Paper

The original paper, "Leader Age, Death, and Political Liberalization in Dictatorships" by Professor Sarah Hummel can be found at https://www.journals.uchicago.edu/doi/pdf/10.1086/707492. The supplemental appendix can be found at https://www.journals.uchicago.edu/doi/suppl/10.1086/707492/suppl_file/181762Appendix.pdf. The replication materials can be found at https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OOLBO9. 

## Variables and Data Sources

From the Appendix:

* **Polity**: The revised combined Polity score (Polity2 in the dataset), calculated by subtracting the 10-point autocracy score from the 10-point democracy score. The resulting measure ranges from -10 to +10. (*Source: Monty Marshall, Keith Jaggers and Ted Gurr. 2011. Polity IV Project, Center for Systemic Peace*)

* **Regime Change**: An indicator variable for whether the country is coded as a different regime type (Personalist, Monarchy, Party, Military, or Democracy) than in the previous year. (*Source: Barbara Geddes, Joseph Wright and Erica Frantz. 2014. “Autocratic Breakdownand Regime Transitions: A New Data Set.” Perspectives on Politics, 12(2):313-331.*)

* **Democratization**: An indicator for whether the country is coded as a democracy, according to the institutional definition of the DDI dataset. (*Source: Jose Antonio Cheibub, Jennifer Gandhi and James Raymond Vreeland. 2010. “Democracy and Dictatorship Revisited.” Public Choice, 143:67-101.*)

* **Death**: An indicator for whether the “effective primary ruler” died a natural death. This explicitly excludes assassinations and retirements. (*Source: Henk Goemans, Kristian Gleditsch and Giacomo Chiozza. 2009. “Introducing Archigos: A Dataset of Political Leaders,” Journal of Peace Research, 12(2): 313-331.*)

* **Age**: The age of the “effective primary ruler”. (*Source: Henk Goemans, Kristian Gleditsch and Giacomo Chiozza. 2009. “Introducing Archigos: A Dataset of Political Leaders,” Journal of Peace Research, 12(2): 313-331.*)

* **Tenure**: The number of years the “effective primary ruler” has been in power. (*Source: Henk Goemans, Kristian Gleditsch and Giacomo Chiozza. 2009. “Introducing Archigos: A Dataset of Political Leaders,” Journal of Peace Research, 12(2): 313-331.*)

* **ln(DGPPC)**: The natural logarithm of GDP per capita. (*Source: The Maddison Project. 2013. http://www.ggdc.net/maddison/maddison-project/home.htm.*)

* **Personalist**: An indicator variable for whether a regime is a personalist dictatorship. Personalist dictatorships are distinguished by the fact that “...control over policy, leadership selection, and the security apparatus is in the hands of...a narrower group centered around an individual dictator” (p. 318). (*Source: Barbara Geddes, Joseph Wright and Erica Frantz. 2014. “Autocratic Breakdown and Regime Transitions: A New Data Set.” Perspectives on Politics, 12(2):313-331.*)

* **Irregular Exit**: An indicator variable for whether the “effective primary ruler” left power through any irregular means other than natural death. This includes any exit that is contravention of explicit rules or established conventions. (*Source: Henk Goemans, Kristian Gleditsch and Giacomo Chiozza. 2009. “Introducing Archigos: A Dataset of Political Leaders,” Journal of Peace Research, 12(2): 313-331.*)

* **Attempted Coup**: An indicator variable for whether a coup attempt (successful or unsuccessful) occurred. This excludes events defined as “conspiracies.” (*Source: Peter Nardulli, Michael Martin, Michael Slana, Sina Toosi and Joseph Bajjalieh. 2013. “The Coup D’Etat Project,” Cline Center for Democracy.*)

## Code

## Computational Requirement
R is required to run all code for this project. All files created using RStudio Version 1.3.959 and R version 4.0.2 (2020-06-22). Libraries necessary to run code include:

* Tidyverse
* MASS
 *** Finish


