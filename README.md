# Classification of Assessment of Trump Administration’s response to the COVID-19 outbreak
![trump](https://s.abcnews.com/images/US/IpsosPoll_Coronavirus_Q1_ApproveDisapprove_061820_v01_KS_hpEmbed_16x9_992.jpg)

- **Dataset Source**
  - https://ropercenter.cornell.edu/ipoll/study/31117363


- **Context of Dataset**
  - The survey asks 6 questions about the Trump Administration’s response to the COVID-19 outbreak along with its impacts, which are presented as below.
    - Q1: Do you approve or disapprove of the way Donald Trump is handling the response to the coronavirus? (Class Attribute)
      - Approve or Disapprove
    - Q2: How concerned are you that you or someone you know will be infected with the coronavirus?
      - Very concerned, Somewhat concerned, Not so concerned, Not concerned at all
    - Q3: Which of the following statements comes closest to your point of view?
      - Opening the country now is worth it because it will keep economic damage to a minimum vs. Opening the country now is not worth it because it will mean more lives being lost
    - Q4: If a safe and effective coronavirus vaccine is developed, how likely would you be to get vaccinated?
      - Very likely, Somewhat likely, Not so likely, Not likely at all 
    - Q5a: Work Situation
      - I am still working from my regular workplace, outside the home, Because of the coronavirus I am working from home instead of from my regular workplace, I normally work from home, I am not currently employed
    - Q5b: Whether lost job due to COVID-19 outbreak 
      - Yes or No
      
  - In addition to the questions, the dataset also contains background information of participants. The attributes are described as below:
    1. id=participant’sid
    2. xspanish=participant’slanguage(eitherEnglishorSpanish)
3. complete_status=indicatingwhetherparticipantsfullycompletedthesurvey
4. ppage=ageofparticipants
5. ppeduc=educationofparticipants(fromthe1stgradetodoctoratedegree)
6. ppeducat=educationlevelsofparticipants(lessthanhighschool,highschool,
some college, bachelor’s degree or higher)
7. ppgender=Genderoftheparticipant(Male/Female)
8. ppethm=Raceoftheparticipant
9. pphhsize=householdsizeofparticipants
10.pphouse = a brief description of house of participants
11.ppincimp = participant’s income
12.ppmarit = marital status of participants
13.ppmsacat = indicating whether participants live in metro area or non-metro area 14.ppreg4 = region of participants
15.pprent = participants house rent
16.ppstaten = state where participants live
17. Q1
18. Q2
19. Q3
20. Q4
21. Q5a
22. Q5b
23.QPID = political party that participants support
24.POLIT200 = indicating whether participants are registered to vote at their current
address
25.ABCAGE = The participants age range
26.Weights_pid = The study dataset(s) contain weight factors that should be
employed in any data analysis. Typically, weights are used in an attempt to assure that the survey sample more accurately represents the population.
