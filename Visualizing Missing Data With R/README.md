# DIAGNOSTIC OF THE MISSING DATA WITH R

## Description
### The Behavioral Risk Factor Surveillance System (BRFSS) Survey Data, 2009
The data is a subset of the 2009 survey from BRFSS, an ongoing data collection program designed to measure behavioral risk factors for the adult population (18 years of age or older) living in households.

### Usage
data(riskfactors

### Format
An object of class tbl_df (inherits from tbl, data.frame) with 245 rows and 34 columns.

### Source 
https://www.cdc.gov/brfss/annual_data/annual_2009.htm

### See Also
the codebook: https://www.cdc.gov/brfss/annual_data/annual_2009.htm

Format: a data frame with 245 observations on the following 34 variables.

### State
A factor with 52 levels. The labels and states corresponding to the labels are as follows: 1:Alabama, 2:Alaska, 4:Arizona, 5:Arkansas, 6:California,8:Colorado, 9:Connecticut, 10:Delaware, 11:District of Columbia,12:Florida, 13:Georgia, 15:Hawaii, 16:Idaho, 1 :Illinois,18:Indiana, 19:Iowa, 20:Kansas, 21:Kentucky, 22:Louisiana,23:Maine, 24:Maryland, 25:Massachusetts, 26:Michigan,27:Minnesota, 28:Mississippi, 2:Missouri, 30:Montana,31:Nebraska, 32:Nevada, 33:New Hampshire, 34:New Jersey, 35:NewMexico, 36:New York, 37:North Carolina, 38:North Dakota, 39:Ohio,40:Oklahoma, 41:Oregon, 42:Pennsylvania, 44:Rhode Island, 45:SouthCarolina, 46:South Dakota, 47:Tennessee, 48:Texas, 49:Utah, 50:Vermont, 51:Virginia, 53:Washington, 54:West Virginia,55:Wisconsin, 56:Wyoming, 66:Guam, 72:Puerto Rico, 78:Virgin Islands

### sex
A factor with levels Male Female.

### age
A numeric vector from 7 to 97.

### weight_lbs
The weight without shoes in pounds.

### height_inch
The weight without shoes in inches.

### bmi
Body Mass Index (BMI). Computed by weight in Kilogram /(height in Meters * height in Meters). Missing if any of weight or height is missing.

### marital
A factor with levels Married Divorced Widowed Separated NeverMarried UnmarriedCouple.

### pregnant
Whether pregnant now with two levels Yes and No.

### children
A numeric vector giving the number of children less than 18 years of age in household.

### education
A factor with the education levels 1 2 3 4 5 6 as 1: Never attended school or only kindergarten; 2: Grades 1 through 8 (Elementary); 3: Grades 9 through 11 (Some high school); 4: Grade 12 or GED (High school graduate); 5: College 1 year to 3 years (Some college or technical school); 6: College 4 years or more (College graduate).

### employment
A factor showing the employment status with levels 1 2 3 4 5 7 8. The labels mean – 1: Employed for wages; 2: Self-employed; 3: Out of work for more than 1 year; 4: Out of work for less that 1 year; 5: A homemaker; 6: A student; 7:Retired; 8: Unable to work.

### income
The annual household income from all sources with levels <10k 10-15k 15-20k 20-25k 25-35k 35-50k 50-75k >75k Dontknow Refused.

### veteran
A factor with levels 1 2 3 4 5. The question for this variable is: Have you ever served on active duty in the United States Armed Forces, either in the regular military or in a National Guard or military reserve unit? Active duty does not include training for the Reserves or National Guard, but DOES include activation, for example, for the Persian Gulf War. And the labels are meaning: 1: Yes, now on active duty; 2: Yes, on active duty during the last 12 months, but not now; 3: Yes, on active duty in the past, but not during the last 12 months; 4: No, training for Reserves or National Guard only; 5: No, never served in the military.

### hispanic
A factor with levels Yes No corresponding to the question: are you Hispanic or Latino?

### health_general
Answer to question "in general your health is" with levels Excellent VeryGood Good Fair Poor Refused.

### health_physical
The number of days during the last 30 days that the respondent's physical health was not good. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### health_mental
The number of days during the last 30 days that the respondent's mental health was not good. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### health_poor
The number of days during the last 30 days that poor physical or mental health keep the respondent from doing usual activities, such as self-care, work, or recreation. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### health_cover
Whether having any kind of health care coverage, including health insurance, prepaid plans such as HMOs, or government plans such as Medicare. The answer has two levels: Yes and No.

### provide_care
Whether providing any such care or assistance to a friend or family member during the past month, with levels Yes and No.

### activity_limited
Whether being limited in any way in any activities because of physical, mental, or emotional problems, with levels Yes and No.

### drink_any
Whether having had at least one drink of any alcoholic beverage such as beer, wine, a malt beverage or liquor during the past 30 days, with levels Yes and No.

### drink_days
The number of days during the past 30 days that the respondent had at least one drink of any alcoholic beverage. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### drink_avg
The number of drinks on the average the respondent had on the days when he/she drank, during the past 30 days. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### smoke_100
Whether having smoked at least 100 cigarettes in the entire life, with levels Yes and No.

### smoke_days
The frequency of days now smoking, with levels Everyday Somedays and NotAtAll(not at all).

### smoke_stop
Whether having stopped smoking for one day or longer during the past 12 months because the respondent was trying to quit smoking, with levels Yes and No.

### smoke_last
A factor with levels 3 4 5 6 7 8 corresponding to the question: how long has it been since last smoking cigarettes regularly? The labels mean: 3: Within the past 6 months (3 months but less than 6 months ago); 4: Within the past year (6 months but less than 1 year ago); 5: Within the past 5 years (1 year but less than 5 years ago); 6: Within the past 10 years (5 years but less than 10 years ago); 7: 10 years or more; 8: Never smoked regularly.

### diet_fruit
The number of fruit the respondent eat every year, not counting juice. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### diet_salad
The number of servings of green salad the respondent eat every year. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### diet_potato
The number of servings of potatoes, not including french fries, fried potatoes, or potato chips, that the respondent eat every year. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### diet_carrot
The number of carrots the respondent eat every year. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### diet_vegetable
The number of servings of vegetables the respondent eat every year, not counting carrots, potatoes, or salad. -7 is for "Don't know/Not sure", and -9 is for "Refused".

### diet_juice
The number of fruit juices such as orange, grapefruit, or tomato that the respondent drink every year. -7 is for "Don't know/Not sure", and -9 is for "Refused".

## Summary
Most of the missing values are in the pregnant (87,76%), health poor (46,12%), drink days (54,69%), drink average (55,1%), smoke days (52,24%), smoke stop (86,53%), and smoke last (65,71%) columns. And a small part is spread in various variations. Based on the visualization that has been made, we conclude that the data belongs to the Missing Not at Random (MNAR) type, which means that there is a systematic relationship between missing data and unobserved values.
