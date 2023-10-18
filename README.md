Most individuals rely on credit to finance vehicles, real estate, student loans, and the start-up of small enterprises. Assessing credit risk data is crucial for financial institutions when deciding whether to offer the loans.

Dataset used for credit assessment was sourced online. Therefore proceed to load the relevant libraries in python which will be used for credit risk assessment.

After the data is loaded, data cleaning is done next to format any inconsistencies and ensure the data is in order to avoid any errors. First check the data types for the columns as In this data set there are a mix types of data which may make data manipulation a bit hard hence convert integers to float. I prefer using floats as it allows me to represent data on plots accurately and ensures compatibility with various libraries.

Once the data is cleaned, data visualisation is next. Histograms will be used to show visual representation of ages. In this data set, shows most people who have loans range 20-40 years. Highest number are in their 20s.

Next, creation of boxplot to visualize the distribution of loan amounts by loan grade.Each box in the plot represents a specific loan grade, and it shows the distribution of loan amounts for that grade. The boxplot provides information about the median, quartiles, and any potential outliers in the data for each loan grade, making it a useful tool for understanding the distribution of loan amounts across different grades. Grade F loans have a median income that is superior to other grades.

The next step,use of scatter plots to provide insights into the relationship between a borrower's debt-to-income ratio, interest rate, and whether they defaulted on their loan. A higher debt-to-income ratio indicates that the borrower has a larger proportion of their income committed to debt payments. In the data set, loans with lower interest rate, lower debt to income ratio have not defaulted while loans with higher interest rate have defaulted.

Count plots of homeownership will be done to provide a visual representation of different types of home ownership among borrowers. In this data set the "RENT" is the most common home ownership type among borrowers, followed by "MORTGAGE." The "OWN" category has the fewest borrowers.
This plot helps one understand the characteristics of borrowers and can help identify potential factors that impact credit risk.
In this case, most of the borrowers are renters, followed by those with mortgage. The least borrowers are home owners

Lastly, relationship between person income and loan amount is established by using scatterplot. In the data set, most borrowers are low income earners and have different intent use for the loans.

Python being an open source gives one access to different libraries that enables you to handle large data sets and easily customize to what you prefer.
