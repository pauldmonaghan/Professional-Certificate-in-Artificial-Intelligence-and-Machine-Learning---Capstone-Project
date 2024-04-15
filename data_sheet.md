# Datasheet

## Motivation

- For what purpose was the dataset created?

The dataset was created for a machine learning competition entitled "Find the best black box optimiser for machine learning" which was a real life competition hosted by NeurIPS that took place in 2020.
- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)?

Twitter and SigOpt provided all data sets solely as sponsors of the Challenge.
Who funded the creation of the dataset?
Unclear to the author of this datasheet, though the dataset is assumed to have been funded by Black Box, the hosting company for the competition 

## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)?

Function 1's data represents sources of radiation in some area.
Function 2's data represents a noisy machine learning model
Function 3's data represents how a given drug adversely affects individuals
Function 4's data represents a business's online sales
Function 5's data represents the yield of a chemical process after processing in some factory
Function 6's data represents scores given to metrics used to measure the standard of a cake by an expert tester
Function 7's data represents a popular and frequently used machine learning model
Function 8's data represents a high-dimension search space (8 dimensions to be precise)

- How many instances of each type are there?

Function 1 has 10 instances of each type
Function 2 has 10 instances of each type
Function 3 has 15 instances of each type
Function 4 has 30 instances of each type
Function 5 has 20 instances of each type
Function 6 has 20 instances of each type
Function 7 has 30 instances of each type
Function 8 has 40 instances of each type

- Is there any missing data?

There is no missing data

- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?

It should be noted that function 3 may contain confidential information, as it is contains measurements of people's adverse reaction to a drug. The outputs of function 5 could also be considered confidential, depending on the specific chemical reaction being investigated.

## Collection process

- How was the data acquired?

Unknown to the author of this datasheet. Just that it was provided by Twitter and SigOpt  

- If the data is a sample of a larger subset, what was the sampling strategy?

It is unknown to the author of this datasheet if the data is a sample of a larger subset for each function.

- Over what time frame was the data collected?

Unknown to the author of this datasheet

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 

Besides sorting the data into arrays and in some cases dictionaries and pandas dataframes, there was no preprocessing/cleaning/labelling of on the data.

- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 

No

## Uses

- What other tasks could the dataset be used for?

The datasets provided were intended to be used specifically for the competition's purposes. As such, it is not advised that the datasets are used for any other tasks.

- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms?

The data at most risk of exploitation in this manner if that of function 3, which contains measurements of people's adverse reactions to a drug. This data in particular should at least be kept in a secure, password protected location to avoid it falling into the wrong hands. Function 5's should be kept similarly secure, depending on the chemical reaction in question - perhaps the reaction could cause harm to people if not undertaken in a sufficiently controlled environment.

- Are there tasks for which the dataset should not be used? If so, please provide a description.

The dataset for function 3 should not be used to try and identify individuals who were part of the trial.

## Distribution

- How has the dataset already been distributed?

There is a starter kit available on GitHub for those wanting to look at the competition today retrospectively (the competition finished at the end of 2020). The kit contains baseline files which appear to contain some data, but it is unclear if the data is complete when coming from this particular source. The dataset provided to participants of this course, however, is complete and does not contain any missing data.

- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?

Unknown to the author of this datasheet. However, there are terms and conditions that can be found on the black box website (https://github.com/rdturnermtl/bbo_challenge_starter_kit/files/4801454/terms_and_conditions.pdf)

## Maintenance

- Who maintains the dataset?

There is no mention of the dataset being maintained or by whom if anyone.
