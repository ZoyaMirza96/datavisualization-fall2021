# __Assignment 4: Interview a Dataset__

### A link to the dataset: [DC COVID-19 VACCINE DEMOGRAPHICS](https://opendata.dc.gov/datasets/dc-covid-19-vaccine-demographics/explore)

## Questions and Answers:

### 1) Which age-group has the highest vaccination rate?
### ANS: People between the ages of 20-44. 

### 2) What observation(s) can be made about vaccination trends amongst different racial groups?
### ANS: Individuals who identify as Native Hawaiian or other Pacific Islander have the lowest number of vaccinations amongst both partially and fully vaccinated individuals, and individuals who identify as Black have the highest number of vaccinations amongst both partially and fully vaccinated individuals in this data set.

### 3) Do these aforementioned observations match vaccination trends reported across the media and news outlets?
### ANS: No, as this dataset shows that the black community has the highest vaccination rate in this dataset. However, this record only shows data from an isolated period and time, and may not be representative of general vaccination trends across the country.

## Steps Taken to Clean Dataset:

### - Data was downloaded as a CSV file
### - Dataset was copied onto another sheet to keep track of any changes made
### - The "AGE_GROUP" column was filtered in ascending order to arrange age groups beginning from "16-19" all the way to "65+"
### - The "RACE" column was filtered in ascending order to arrange data representing "American Indian or Alaska Native" at the top and "Native Hawaiian or Other Pacific Islander" at the bottom
### - The "STATUS" column was filtered to sort "Partially Vaccinated" and "Fully Vaccinated" individuals, and omit blank spaces and missing information in the dataset
### - The "RACE" column was filtered again to combine both "Partially Vaccinated" and "Fully Vaccinated" individuals corresponding to the same racial group. For example, this showed vaccinated individuals for "American Indian or Alaska Native" at the top and vaccinated individuals for "Native Hawaiian or Other Pacific Islander" at the bottom
### - Opened up a blank sheet and shifted this sorted data onto a Pivot Table 
### - Used the sum category to calculate percentages and figures to answer the questions I was asking. For example, total number of vaccines administered per age group, total number of vaccines administered in relation to a specific racial group.

## Sample Headline and Nut Graf:

### HEADLINE: Vaccine Access Made More Equitable in Washington D.C.

### NUT GRAF: Studies conducted by the CDC in the past year have revealed a [disproportionate rate](https://www.cdc.gov/coronavirus/2019-ncov/community/health-equity/racial-ethnic-disparities/disparities-deaths.html) of COVID-19 deaths among some racial and ethnic minority groups in the United States. A medical survey that focused on certain cities and states demonstrated that the outbreak of the Delta variant had led to a stark incline in virus contractions in Black and Hispanic American communities versus others. A demographic evaluation showed that, overall, these communities had less access to vaccines and general healthcare facilities, hence, leading to low vaccination rates.


