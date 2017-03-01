# aj

This Python 3 program takes an Adjuster aggregate report, which contains data for all live ad campaigns for the specified time range, and returns a copy of the report with an additional ID number column. This ID number, called the Salesforce number (SF#) is obtained from the ad campaign name. This column is necessary for other teams to be able to analyze the Adjuster data using Tableau.

This program uses the OpenPyXL package to interact with Microsoft Excel files and the pandas package to alter the input .xlsx file.

Since ad campaign names are manually entered by whoever set up the campaign on WebMD's ad server, the formatting of the names is inconsistent. Due to this, the SF# column was previously produced by manually copying the ID number for each campaign.

An example Adjuster report is included to demonstrate how the program works.
