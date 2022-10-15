<font size="+3"><strong>No Show Appointments Data Analysis</strong></font>

## Dataset

This dataset collects information from over 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

*"ScheduledDay"* tells us on what day the patient set up their appointment.

*"Neighborhood"* indicates the location of the hospital.

*Scholarship* indicates whether or not the patient is enrolled in Brasilian welfare program [Bolsa Família](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)


## Question(s) for Analysis
$1$. What neighourhoods have the most and least proportion of patients that showed up for appointment?

$2$. Was SMS recieved a major factor to patients showing up or not showing up for their appointment?

$3$. Did Patients who ae addicted to Alcohol miss their appointment more than others?


## Summary of Findings

**1**. For Research Question 1, We can see that patients living in "**ILHA DO BOI**" and "**AEROPORTO**" showed up more for their appointments with only about **9%** and **13%** of them not showing up for appointment respectively.
In contrast with over **20%** of the entire dataset that did not show up for their appoinments.

On the Contrary, neighbourhoods "**SANTOS DUMONT**" and "**SANTA CLARA**" have the highest proportion of patients who did not show up for their appointments with over **29%** and **27%** of patients living in those neighbourhoods not ahowing up respectively.

Neigbourhoods "**ILHAS OCEÂNICAS DE TRINDADE" AND "PARQUE INDUSTRIAL"** both appeared only **3** times in the entire dataset so their outcomes in this analysis exhibited outlier behaviours.

**2**. For Research Question 2, it seems that contrary to what I would have assumed SMS received seems to have been a negative factor as to whether a patient showed up for appointment
Or that SMS recieved has no influence on whether or not the patients show up for appointment
That is infact a **Limitation** of this study as I did not check for any correlation between the "*sms_recieved"* and *"no_show*" variables

**3**. For Research Question 3, From over 3,000 patients who suffer from alcoholism, over **80%** of them showed up for appointment,which is almost the same proportion with that of the patients who do not suffer from alcoholism.
So, we can infer from this dataset that patients who suffer from alcoholism did not statistically miss appointment more than those that do not.
