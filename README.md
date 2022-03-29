# Mental Health in Gamers: An Analysis
## Data Analysis Bootcamp 2022

The popularity of gaming has increased over many decades, as accessibility, connectivity and affordability through multiple platforms have made it easier for more people to play games than ever before. Over the last decade, we have also seen an increase in mental health awareness. Whether it be related to the societal impacts from the costs of living, the changing composition of the “traditional family” model, the geopolitical landscape or increased education, there is an increased acceptance and reporting of mental health disorders now than ever before.

For our group project, we wanted to investigate the prevalence of mental health conditions amongst video game players. We found a suitable dataset on Kaggle, which was derived from a study undertaken by German researchers Marian Sauter and Dejan Draschkow (Sauter & Draschkow, 2017). In this survey, players were asked a ranged of questions about their gaming habits, in particular:
* Playstyle (e.g. Singleplayer or Multiplayer);
* How many hours they spend gaming per week;
* What is their most played video game;
* Why they play video games;
* What platform they play videogames on (e.g. PC, Console, Mobile/Tablet).

Participants were also asked to complete four different psychological questionnaires that assessed their mental health. The questionnaires used were:
* Generalised Anxiety Disorder scale (GAD-7; Spitzer et al., 2006)
* Satisfaction With Life scale (SWL; Diener et al., 1985)
* Social Phobia Inventory (SPIN; Antony et al., 2006)
* Single Item Narcissism Scale (SINS; Konrath et al., 2014)

### Research Questions
After reading about the data, three research questions arose:
On average, how many hours do people spend gaming per week?
Is there a correlation between mental health disorders and amount of time spent gaming?
Is there a relationship between mental health disorder prevalence and different demographics?

### Analysis Plan
We are using the **GamingStudy_Data.csv** file obtained from [Kaggle](https://www.kaggle.com/datasets/divyansh22/online-gaming-anxiety-data). Based on the research questions developed, our analysis plan is as follows:
* Obtain demographic information for participant population
* Create graphs to describe and analyse population gaming data and mental health questionnaire scores.
* Create heatmaps and choropleth maps to visualise and compare average population data globally.
* Undertake statistical analyses in the form of t-tests, ANOVA, and linear regression to determine any relationships between mental health and gaming habits.

### Repository Navigation
* The raw study data, and the jupyter notebook our group developed to clean this data, can be found in the [Raw Data and Cleaned Code](https://github.com/jsacharz/Project_01/tree/main/Raw%20Data%20and%20Clean%20Code) folder.
* The cleaned data that was developed from the data cleaning notebook is labelled as **"cleaned_data.csv"**. From this, subsequent CSVs were created and appended with the initials of the person who last cleaned the data. The final CSV that was utilised in our analyses is [cleaned_data_js_sc_rg.csv](https://github.com/jsacharz/Project_01/blob/main/cleaned_data_js_sc_rg.csv)
* All image files related to analysis can be found in the [Image Files](https://github.com/jsacharz/Project_01/tree/main/Image%20Files) folder. The images include a range of analysis graphs and choropleth maps that were generated from our analyses.
* Analysis completed by Sarah Casauria can be located in the folder [SC Clean and Analysis](https://github.com/jsacharz/Project_01/tree/main/SC%20clean%20and%20analysis). This includes two jupyter notebooks describing the generation of a participant heatmap and choropleth maps. 
