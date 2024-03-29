# DevFlair Research Website
**This web page contains all the documents and reports of the final year research of team 2022-014.**

## DevFlair: A Framework to Automate the Pre-screening Process of Software Engineering Job Candidates

* Supervisor: **Professor Samantha Thelijjagoda** (Dean, SLIIT Business School)
* Co-supervisor: **Dr. Dilini Rajapaksha** (Postdoctoral Research Fellow at RMIT University)

## Abstract
The HR department of a technology company receives hundreds of job applications for each Software Engineering related vacancy. The ideal candidate must fulfill the job requirements while having the required personality traits. Identifying the technical skills of a candidate by looking at the curriculum vitae may appears to be easy during the pre-screening process. However, using an open-ended questionnaire, or analyzing the candidate's activities on online platforms like GitHub would help the recruiter to obtain a more accurate and deeper understanding of the technical skills.  In this paper we propose “DevFlair”; a framework for personality and technical-skill analysis which uses data from social media, GitHub, and open-ended questionnaires to predict the Big-Five personality traits, analyze technical skill expertise, and analyze the experience in using industry-related online platforms of Software Engineering job candidates. After analyzing, the candidates are ranked according to their personality and skill levels. In addition, the framework provides a variety of filtering options for the recruiter to select suitable candidates. “DevFlair” uses Natural Language Processing and Machine Learning methodologies enabling the recruiters to effortlessly automate the pre-screening process and recruit the best possible candidates, minimizing human error. We conducted the personality prediction experiments using a social media posts dataset annotated with gold-standard Big-Five personality labels. We trained FastText classification models and compared their accuracy against other state of the art classification models. The comparisons concluded that the FastText classification models substantially outperform the state of the art classification models when predicting Openness, Conscientiousness, and Agreeableness personality traits.


## Research Components and Sub Objectives

| **ID**     	| **Name**              	| **Research Component**                	| **Objective**                                                                                                                                                         	|
|------------	|-----------------------	|---------------------------------------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| IT19129204 	| Jayasekara R.T.R      	| Personality Prediction Model      	| Identify the Big Five personality traits of a Software Engineering job candidate using social media data. 	|
| IT19147024 	| Kariyawasam K.G.S.S.K 	| Ranking and Recommendation Model      	| Implementing a ranking system to identify best candidates considering both personality and technical skills aspects.       	|
| IT19126234 	| Jayasinghe S.L        	| Technical Skills Recognition Model    	| Implementing a model to assess the technical skills of Software Engineering job candidates with a questionnaire.                                                      	|
| IT19121352 	| Kudarachchi K.A.N.D   	| Technical Skills Usage Analysis Model 	| Analyze technical skill based data from GitHub and develop a model to identify the technical skill usage with the platform.                  	|
