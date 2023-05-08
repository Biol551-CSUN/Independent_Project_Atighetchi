# Independent_Project_Atighetchi


For my final project, I decided to visualize some of the data from my Thesis/Dissertation and potentially use these visualizations in my thesis!!


## Systemic Lupus Erythematosus (SLE)

Systemic Lupus Erythematosus or SLE is an autoimmune disorder that is characterized by systemic inflammation and damage to tissues. 
The genetic basis of this disease is not well studied in individuals of differing ancestries, and so my thesis focuses on broadening 
this disparity by including a large cohort of diverse ancestries including those of Hispanic ethnicity, European/White, Asian, African Americans, and others to investigate the genetic and chronic factors associated with an increased risk in SLE.

This project is a culmination of my thesis work and so will include much of the data and analysis behind my thesis work.  

## Metadata + Data Cultivation - [All of Us Workbench Metadata Details](https://www.researchallofus.org/data-tools/methods/)

The data I am using for this project comes from NIH's All of Us Researcher Workbench and uses a collection of data from electronic health records, survey answers, physical measurements, and wearable devices like Fitbits. Registered Tier data are adjusted to lower the chance that any researcher can identify any one participant. For example, researchers cannot see a participant’s exact location, only the state where they live.

The curated dataset I am using may be accessed by registered researchers in the All of Us Researcher Workbench. Registered Tier data includes individual-level data from surveys, physical measurements taken at the time of participant enrollment, longitudinal Health Records, and data from wearables like Fitbit. This individual-level data must be analyzed within the secure Researcher Workbench

**For my project**, I employ the use of two separate datasets:

(1) A demographic dataset of SLE affected individuals (cases) and individuals without any autoimmune disorder (controls) from the All of Us workbench. This demogrpahic dataset includes measures from self-surveys of indviduals outlining their racial, ethnic, age, and demographic backgrounds

| Column Name  | Data Type |                                         Description |
|:-------------------------:|:----------------:|--------------------------:|
|  person_id   |  Numeric  |             Unique ID of every patient in a dataset |
|    gender    | Character |                          The gender of each patient |
|     age      |  Numeric  |                          Age of each unique patient |
|     race     | Character |                         Race of each unique patient |
|  ethnicity   | Character | Hispanic or non-Hispanic Ethnicity for each patient |
| sex_at_birth | Character |                       Sex at Birth for each patient |
|    group     | Character |          Either denoted as SLE "Cases" or "Control" |


(2) A "comorbidity" dataset that includes participant level data on Electronic health records of individuals affected with SLE. This dataset is also from the All of Us Researcher Workbench and includes records of visits of these SLE individuals based on the selection of 6 of the most common SLE disease comorbidities to allow for analysis of severity between different racial and ethnic groups on their heterogeneous manifestations of SLE. 

| Column Name  | Data Type |                                         Description |
|:-------------------------:|:----------------:|--------------------------:|
|  person_id   |  Numeric  |             Unique ID of every patient in a dataset |
|    gender    | Character |                          The gender of each patient |
|     race     | Character |                         Race of each unique patient |
|  ethnicity   | Character | Hispanic or non-Hispanic Ethnicity for each patient |
| standard_concept_name | Character |  Comorbidity values separated by commas |
| commor_score |  Numeric  | Denotes severity of SLE on an arbitrary scale of 1-6|




![](https://www.nih.gov/sites/default/files/styles/featured_media_breakpoint-medium/public/research-training/initiatives/pmi/pmi-all-of-us-logo.jpg?itok=BDi3j90Z&timestamp=1476283809) 
