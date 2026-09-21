Below is a brief description of each variable included in the datasets. Please note that not all questions were asked in every survey. For this reason, some variables may contain a large amount of missing data.

	- Timestamp: date when the survey was completed.

	- Country: country of residence of the respondent.

	- ISO.3166.1.a2: two-letter ISO country code.

	- Region: region within the respondent’s country.

	- ISO.3166.2: ISO code of the region.

	- Language: language in which the survey was completed.

	- Reach: number of people for whom the respondent provides information.

	- Cases: number of cases reported by the respondent.

	- Visibility: number of people the respondent must inform if he contracts the virus.

	- Recovered: number of cases already recovered from the virus.

	- Fatalities: number of deaths caused by the virus.

	- RecentCases: number of cases with symptom onset within the last 7 days.

	- RecentCases14: number of cases with symptom onset within the last 14 days.

	- PositiveTest14Days: number of positive tests in the last 14 days among symptomatic individuals.

	- PositiveTest07Days: number of positive tests in the last 7 days among symptomatic individuals.

	- LongCovid: number of people with persistent symptoms after recovering from the virus.

	- StillSick: number of people who are still sick (not recovered).

	- Tested: number of people who underwent testing.

	- Positive: number of those tests that were positive.

	- Hospital: number of cases requiring hospitalization.

	- Severe: among those hospitalized, number of severe cases.

	- ICU: number of cases admitted to the ICU.

	- Vaccinated: number of vaccinated individuals.

	- RecentVaccinated: number of individuals vaccinated in the last 7 days.

	- VaccineSideEffects: number of people who experienced side effects from the vaccine.

	- RefuseVaccine: number of people who refused vaccination.

	- ContactsDoctors: number of doctors known by the respondent.

	- Surveyfirst: boolean indicating whether this is the respondent’s first survey.

	- Surveyknown: boolean indicating whether the respondent already knew about the survey.

	- Surveyforward: boolean indicating whether the respondent forwarded the survey.

	- Dataset: type of dataset in which the survey was recorded.

	- Cookie:  created on the participants’ browser or device to provide identification for the user.

	- Campaign: campaign identifier when the response originates from a specific dissemination campaign. 



The dataset is organized as follows:

First, there are several folders corresponding to different stages:

	- March 2020-May 2020 --> emergence of the virus and first reported cases.

	- May 2020-Dicember 2020 --> first waves and lockdown. In May, we changed our survey collection method.

	- January 2021-June 2021 --> introduction of the first vaccines.

	- July 2021-March 2022 --> the emergence of the Delta and Omicron variants.

	- April 2022-Dicember 2023 --> with relative control, it begins to be treated as an endemic disease.

	- January 2024-August 2025 --> normalization and ongoing surveillance.


Upon entering any of these folders, you will find subfolders named CC-aggregate, where CC corresponds to the country’s ISO code. These subfolders contain the data for all countries included in that specific stage.

Inside a country’s folder, you will find up to four additional subfolders, which separate the country’s data according to the type of survey used to collect the information. The number of subfolders may vary depending on how many types of surveys were conducted in that country at that stage.

**As a clarification, within the first stage, in addition to the country-specific subfolders, you will also find a subfolder named twitter. This folder contains the data from countries where Twitter was used at some point as a method for collecting survey responses. Only aggregated survey data are included in these datasets; no individual-level Twitter responses are provided. Each row summarizes the responses collected for a given survey, including the number of answers and the percentage of responses in each category. The variables included are:

	- Country: ISO letters of the country.

	- Start.time: time and date in which the survey started.

	- End.time: time and date in which it ended. 

	- Number.of.answers: indicating the numer of people you answered the survey.

	- Percetage_0: percentage of people whose answer was 0.

	- Percentage_1: percentage of people whose answer was 1.

	- Percentage_2: percentage of people whose answer was 2.

	- Percentage_3_or_more: percentage of people whose answer was 3 or more.

	- Question: question the survey made.

	- Link: link of the survey.











