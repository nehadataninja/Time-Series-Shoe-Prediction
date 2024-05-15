# Time-Series-Shoe-Prediction
XN Sponsor Organization:  ![image](https://github.com/nehadataninja/Time-Series-Shoe-Prediction/assets/155708653/de375765-ea5c-4cfa-8672-0c645f19c008)

Capstone Project Title & Scope:

Title: Predictive Modeling & Dashboarding Analysis for Sneaker Resale Market

Description      

An Oklahoma company created the first pricing algorithm designed to empower both buyers and sellers in the sneaker resale market. The goal of this project is to use the company's proprietary sneaker database to generate new, interesting insights about the sneaker resale market and identify trends that resellers can use in price negotiation, inventory management, and other aspects of day-to-day operations. This will involve several different steps for the students, including: - Preprocessing and analyzing existing dataset of sneaker resale data. - Developing machine learning models / algorithms to identify trends in the data. - Building a dashboard using a BI tool to showcase data visualizations that capture the trends & insights gathered. - Researching other data that can improve the accuracy and predictability of the analysis.

Deliverables      
By the end of the project, students will provide (a) Analysis of the existing dataset of sneaker resale data, (b) Understanding of features that most impact sneaker resale prices, and (c) Identification of new data sources for future use.

The final deliverables will include:
- All source code.
- A presentation explaining the analysis & model development process and outcomes.
- An interactive dashboard that displays key trends and insights in the sneaker market that the company can use going forward in its analysis of the sneaker market.

At the beginning of the project, the students will be given guidance as to how to best get up to speed with the sneaker market and will be given access to the data prior to the project start. The data is several thousands of records (or can be in millions) and is in a SQL database which students will either have access to or be given a CSV file.

 

Data Dictionary

Feature	Type	Description
SKU	string	SKU, sneaker's unique identifier (not unique to size however)
CONDITION	string	Sneaker's condition as categorized by marketplace it was sold in (our primary focus is 'is_new' and 'Brand New' condition)
SIZE	string	Listed size of sneaker
GENDER	string	Gender category
SOLD_AT	timestamp	Date and time sold
SOLD_PRICE	float	Price sold
SOURCE	string	Source of sale record
SIZE_VALUE	float	Sneaker size, as a float (excluding string values)
BRAND	string	Sneakr brand
NAME	string	Sneaker name
COLORWAY	string	Officially listed sneaker colorway
COLOR	string	Sneaker's estimated primary color
SILHOUETTE	string	Sneaker's silhouette
RETAIL_PRICE	int	Original retail price
RELEASE_DATE	timestamp	Date sneaker was released
IS_COLLAB	boolean	Whether sneaker is a collaboration (TRUE if yes, FALSE if not or data unavailable)
COLLABORATOR	string	Name of collaborator, if available
