# **Kickstarting with Excel**

## **Overview of Project**
	This project is an in-depth analysis of the Kickstarter Database, which contains data pertaining to campaigns
	intended to raise funds for artistic projects in different disciplines. The database contains 4,114 entries and includes
	a wide variety of dimensions that allows for a wide variety of questions to be asked.

### **Purpose**
	The main objective of this Analysis is to answer a few questions in relation to a specific campaign that was recently launched. 
	Louise a Theater Play producer succesfully launched a kickstarter campaign to fund her Play Titled "Fever" and
	wants to compare her results to those found on the ***"Kickstarter.xsls"*** database. And possibly try to find any correlation between 
	the time in which the campaign was launched and the funding goals.

## **Analysis and Challenges**
	While performing the analysis necessary to answer the questions on this project, there were some challenges that were intefereing with
	obtaining a clear and accurate. The first challenge was having the Categories and Subcategories in the same field, that would make 
	the goal of finding plays less accurate as they be interconnected with all theater productions. The solution was to perform an action called 
	"Text to Columns" and separating the information to use only "Plays". Another challenge was the format in which the date was recorded,
	as it was collected as Unix and needed to be converted.

### **Analysis of Outcomes Based on Launch Date**
	Every campaign at its conception had the posibility to be successful or to fail, and that was stated in the database used. With the use of their outcome 
	and the date of start and finish, we were able to find which times of the year were the most successful and the least favorable for the campaigns.
	Using a Pivot Table and a Pivot Chart "Line chart" we were able to visually identify the corelations between time and outcome.

### **Analysis of Outcomes Based on Goals**
	When analyzing the outcome ofkickstarters campaigns one more factor to consider was the corelation that the goal could have with the results of the campaign.
	For that reason we decided to determine the percentages of campaigns that had been successful, failed or cancelled. and compare them to the goal amount and
	create a graph that could help us visualize the connection between the Goal and the outcomes.

### **Challenges and Difficulties Encountered**
	The first challenge was determining if on the correlation between Outcome and Launch dates, we wanted to consider the years or simply use months. By including
	the years it would make the visualization more dificult to read and give confusing readouts. The second challenge was when measuring the Outcome based on goals
	the percentage of cancelled campaigns were "0" and including it on the visualization would become unecessary, which solution was to leave out of the graph.

## **Results**

- What are two conclusions you can draw about the **Outcomes based on Launch Date**?
	After Analyzing the outcomes based on Launch Date, we have come to the conclusion that the most successful time of the year to launch a campaign intended to
	raise finds for a Theater Play is the month of May progressively declining towards September, with another small peak on October.
	We also discovered that the month with the least activity is the Month of December, which could be related to the Christmas Holidays.

- What can you conclude about the Outcomes based on Goals?
	When analyzing the Outcomes and how they relate to the campaign Goals, is that there is a direct correlation between the amount of money intended to be raised
	and the outcome, meaning that the CAmpaigns with smaller goals had a higher rate of success than those that a hihg goal. We could also conclude that the reason 
	for which those campaigns failed was because their goal was too ambitious.

- What are some limitations of this dataset?
	A limitation of this dataset was that there was no Producer or Production company included on it, therefor we could not know if another reason for which the campaigns
	would fail or succeed was related to the reputation or fame of those responsible of the realization of such productions.

- What are some other possible tables and/or graphs that we could create?
	Another graph that could have been created was the "Correlation between the # of Backers and the Type of productions" That would have also helped us know what type of 
	productions received more support by popularity apart from the amount of money pledged. This could help better strategize the projects to a specific audience and budget.