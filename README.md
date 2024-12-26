<h1>A Study of Default: Lending Club</h1>

<h2>Description</h2>
This project was the final deliverable for my graduate R programming course, R for Data Science. My group chose Lending Club's loan book, a comprehensive dataset from one of the largest peer-to-peer lenders, as the foundation for our analysis. The primary objective was to identify the key factors influencing loan defaults and develop effective models to predict this phenomenon. My contributions focused on the modeling process, which included data preprocessing, variable selection, and the building of predictive models to identify patterns of default, using namely, logistic regression. The accompanying PDF provides detailed commentary and analysis, while the Rnw file used to generate the report has also been included for transparency and reproducibility.
<br />

<h2>Languages Used</h2>

- <b>R</b>
- <b>SQLite</b>

<h2>Program walk-through:</h2>

<p align="left">
1.) Make sure all packages are installed and loaded. <br/>

<br />
2.) Download the loan data csv file (accepted_2007_to_2018q4.csv) from the link: https://www.kaggle.com/datasets/wordsforthewise/lending-club/data. <br/>

<br />
3.) After the data is downloaded, upload the data into a DB Browser SQLite database and title the table it creates "accepted". <br/>

<br />
3.) With the data loaded into the database and the table named correctly, copy the file path of the database on your machine and replace it with the file path you see in the "dbConnect" function. More specifically, this will passed to the the "dbname" argument in the "dbConnect" function. Do this for all the code files. <br/>

<br />
4.) First, run the file "Clean_data.qmd" as it will prepare the data that will ultimately be used in the rest of the analysis. Next, run the "Final Project.qmd" file where the main analysis is conducted. All the results should load and appear once the previous steps are fulfilled. <br/>

<br />
Note: The Rnw file is provided for reference, rendering it will produce the pdf already available in the repository. <br/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
