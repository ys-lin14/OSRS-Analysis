# OSRS-Analysis
Attack speed or accuracy?
A project investigating experience rates and hit probabilities in the game Old School Runescape (OSRS) to satisfying my curiosity.

Contents:
* data (rpg_data.csv, scim_data.csv, combined_data.csv, combined_probability_data.csv) 
  * consists of Defence and Hitpoint experience recorded in Microsoft Excel over 6 hours of playing OSRS
  * combined_data contains the time in 10 minute intervals, cumulative experience, experience type along with the weapon used
  * combined_probability_data contains the number of successful hits, total number of hits, their ratio along with the weapon 
  
* linear_regression
  * reading and writing CSVs along with cleaning and combining dataframes using pandas
  * ordinary least squares linear regression from scratch and using stats from SciPy
  * data visualization using Seaborn scatter plots
  
* probability
  * more dataframe manipulation using pandas
  * tests hypotheses using the Normal (Z-Test) and Student distribution (T-Test)
    * functions created to calculate power, test statistics and p-values / uses existing functions from the stats module
  * visualizes data using Seaborn through the use of scatter plots and kernel density estimate plots
  * uses Seaborn lineplots and the matplotlib fill between option to create visual aids representing the rejection regions of the hypotheses test 
  
Game Context:
The data was obtained from training my defence pure at monks in Edgeville. Presented with an iron scimitar which had attack bonuses but was slower versus a faster Event RPG (cosmetic weapon) without any attack bonuses, I wished to determine the difference between the two.

References\
*Old School Runescape* [Game]. (2013). Cambridge: Jagex Ltd.
