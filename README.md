# Communicate_Data_Finding_Fifa19
This project is divided into two major parts. In the first part, I conducted an exploratory data analysis on the dataset. 
I used Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, 
oddities, patterns and relationships. The analysis in this part is structured, 
going from simple univariate relationships up through multivariate relationships.

In the second part, I took my main findings from my exploration and convey them to others through an explanatory analysis. 
To this end, I created a slide deck that leverages polished, explanatory visualizations to communicate my results.


## DataSet
This dataset includes detailed attributes for every player registered in the latest edition of FIFA 19 database. 
It consists of 18207 observations, 88 features. 
Features included are FIFA 2019 players attributes like Age, Nationality, Overall, Potential

The dataset can be found here: https://www.kaggle.com/karangadiya/fifa19

## Summary of Findings
### Univariate Exploration
- change value, wage and release clause from strings to numbers and remove all currency symbols and change the "M" and "K" to 
corresponding zeros so we can use them in numerical values later
 - changing Height and Weight to numerical kg and cm
 - I started the cleaning with 18207 observations, 88 features. 
After i removed columns not needed for my analysis and also removes null values. 
There are 16,643 observations in the dataset with 45 features to work with. 
 - remove players that are above 40 as they were only 4
 - most of the player in our data in thier 20s. and its slightly postivie skewed
 - most players have height from 175cm to 188cm
 - we removed unnecessary columns such as photo, flag and so on
 - checked for null and removed them
 - fixed value, wage and release clause formats
 - fixed Height and weight formats
 - scale value, wage and release clause

### Bivariate Exploration :

- In this section, investigate relationships between pairs of variables in my data.
- Of all playing position, Right Forward players are valued more and have more variaty in values. 
Right wing back position and Left wing back position are valued lowest.
- most players in the data have a normal body type. Only few players have a stocky body type.
- player with st postison valued more than the rest of the positions
- A strong correlation between Acceleartion and sprint speed
- Acceleration has a negative correlation with Weight, Height and Strength
- Value has postive correlation with Wage and release clause

### Multivariate Exploration

 - Create plots of three or more variables to investigate my data even further
 - will make the value in ranges " superhigh, High, medium, low, superlow" so we can visualize it correctly
 - we see here that the super high values are above the overall of 75 and between the age of 18 to 32
 - Most of the younger players weighs lesser and they also have more of a lean body type.
 - Players whose work rate is High/High, High/Medium have a high acceleration and the Low/Low have a lower acceleration.

key insights for the presentation:
Most of the younger players weighs lesser and they also have more of a lean body type. Players whose work rate is 
High/High, High/Medium have a high acceleration and the Low/Low have a lower acceleration.
