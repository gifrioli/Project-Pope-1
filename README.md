# Project 1

This was the first project of the Lede Program for Data Journalism 2025 at Columbia University.

+ Objective:

I was curious to learn how to use the Google Fact Check API, and given the number of conspiracy theories about the Pope that I fact-checked this year, I thought it would be a good starting point.

The API gathers data on fact-checks published by agencies around the world, using a small request form from Google that news organizations add to their websites. This is common practice for fact-checkers, and with each publication we make, we fill out this tool at the end of our reports.

Data includes the claim, the verdict given by fact-checkers about the analyzed content, the date, and other additional information that is filled out in a rather unorganized way, such as the social network and the author of the post. I decided not to use these last two pieces of information precisely because there is a significant lack of standardization, which would make analysis very difficult.

The API documentation is at: https://developers.google.com/fact-check/tools/

+ Analysis:

The code I wrote to request the data is in the file "Data Request - API Fact Check Tool." The results were saved in the Excel file "factcheck_pope_results.xlsx."

+ Findings:

The generated spreadsheet had more than 800 rows, and to analyze it, I started with some main questions I wanted to answer about fact-checks related to the Popes.

The code I created to analyze the data and generate charts is in the file "Data Analys."

At a certain point during the analysis, I realized I needed to translate the claims column into a single language in order to understand the keywords related to lies about the Pope. This new spreadsheet was saved in the Excel file "claims_traduzidas." All claims are in English.

For the research on the main words related to the lies, I also needed to use KeyBERT, a technique that identifies the most relevant words or phrases in a text.

+ Results:

The results were used to write a short report about lies related to the Popes and their growth, especially in 2025. The text was published on a simple website, using one of the templates created by Jonathan Soma.

In the end, the data was not as interesting as I had expected, and was somewhat obvious. I also wanted to make a better website, but didn’t have time for everything. In any case, I hope you enjoy it a little!
