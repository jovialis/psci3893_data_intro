# PSCI 3893: Intro to Data Manipulation with R
##### Prof. Kim, Fall 2021 @ Vanderbilt University
## Background
Data is the new gold. Today, it backs everything from policy decisions to academic research to business strategy. Regardless of your career trajectory, it's essential that you develop the basic working skills needed to make informed decisions about data, where to collect it, and how to utilize it.

There are a variety of tools available for data analysis, and they are often closely entertwined with the field of Computer Science. Data scientists utilize programming languages like Python and R to gather, manipulate, and analyze datasets. Having a basic working proficiency in one or more of these languages will prove invaluable.
## Objective
In this project, you will learn to utilize the R programming language for basic data cleaning, manipulation, and analysis. You will then apply your new skills and analyze your own YouTube data! You will demonstrate your knowledge by turning in a report of your YouTube search history from January 2021 to August 2021. 
## Procedure
1. Navigate to [Google Takeout](https://takeout.google.com), Google's data reporting portal. Ensure that you are logged into a Google account on which you use YouTube. 
2. Select "YouTube" from the platform options. Ensure that the "format" is set to "JSON."
3. Click "Download." You should either recieve a download immediately, or Google will email you once your data export is completed.
4. Unzip the download and find `search-history.json` in the folder under `YouTube and YouTube Music/history`.
5. Move `search-history.json` to the same directory as this repository's `notebook.Rmd`.
6. Open `notebook.Rmd` in R studio. Read through the code and comments to understand what each command does and how we are manipulating your data.
7. Execute the notebook. Look for a file named `my_youtube_data.csv` generated in this directory. Open it in Excel to view your report!
## FAQ
- **Data Privacy:** We understand the value of your data and by extension the importance of your privacy. You may remove any information from the final report that you do not wish to share with our graders (including but not limited to searches, watched videos, etc.). Furthermore, your final report will be graded anonymously; your data will not be associated with your class record in any capacity beyond completion.