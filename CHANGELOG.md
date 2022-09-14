# Changelog

## 2022-09-12

### Changed

- Consolidated six scenarios down to three based mostly on vaccinated guidance
- Deleted the Unvaccinated Pathways because there is no longer different guidance based on vaccination status. 
- Added T208 and T209 to replace guidance for exposed individuals and remove references to differences in guidance based on vaccination status (replaced throughout). 
- Edited the definition of exposure to reflect updated guidance.
- Edited messages referencing quarantine to say “take extra precautions” rather than quarantine.
- Updated links due to archiving of old pages and introduction of new pages. 
- Removed references to “6 feet” guidance. 

# Changelog

## 2022-06-22

### Changed

- Changed language of Q39 to reflect recent changes to recommendations for pediatric COVID-19 vaccination. 
- Added a pathway redirecting vaccinated users under 2 years old to seek appropriate care. 

## 2022-03-23

### Changed

-	Added Messages to reflect updated [Quarantine and Isolation](https://www.cdc.gov/coronavirus/2019-ncov/your-health/quarantine-isolation.html?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fcoronavirus%2F2019-ncov%2Fif-you-are-sick%2Fquarantine.html) Guidance. New messages are MSG308-MSG313 and testing messages T204-T207.
-	Changed language in the bot and documentation referring to “full vaccination” to reflect the new “up to date” with vaccination language.
-	Deleted a question regarding PPE usage because those users are already asked if they were exposed. Affects Former Q28.
-	Deleted a question that asked pediatric users if they were in a group setting (redundant because users also indicate whether they were exposed). Affects former Q9-PED (Repeated at Q12-PED, Q16-PED, Q19-PED, Q27-PED, Q48-PED, Q51-PED)
-	In prior versions of bot, there were separate pathways for some users depending on whether they were experiencing primary symptoms or only secondary symptoms, however users were already getting the same answers regardless because there is no longer a difference in guidance based on which symptoms one experiences. Version 72’s documentation condenses these pathways into simply “symptomatic” and “asymptomatic.” These changes are largely just to the documentation, since users already were not getting different answers based on which symptoms they had.
-	Edited the endcap and intro language to reflect new community levels guidance.
-	Updated the list of underlying medical conditions to reflect updated guidance. Added primary immunodeficiency, physical inactivity, and some disabilities (including Down syndrome).
-	Minor language edits to MSG19, T102, Q201, Q19-PED.
-	Updated the definition of “close contact” in accordance with guidance updates and removed some references to the term “exposure.”
-	Removed housing at institutes of higher education from the list of congregate care settings to reflect that this group has been asked to follow general guidance. 


## 2022-01-10

### Changed

- Added a fully vaccinated pediatric pathway, reflecting an expanded access to vaccines for children.
- Updated vaccinated and unvaccinated endcap to warn users of important pending updates, stating: “This tool is currently in the process of being updated to align with the latest quarantine and isolation guidance updates. For the most up-to-date recommendations on isolation and quarantine, please visit CDC’s Quarantine and Isolation page.”
- Fixed formatting of endcap list of links to be in sentence case.
- Updated references to only the Delta variant to reflect the pervasiveness of Omicron, to say “variants such as Delta and Omicron.”
- Added Q38-PED (In the last 10 days, have you been tested for the coronavirus that causes COVID-19) to the unvaccinated pediatric pathway and updated the pathway to include responses that reflect whether the user tested positive, negative, has a test pending, or did not take a test.
- Added MSG306 and MSG307 for pediatric users who tested positive.
- Edited the age ranges for the vaccinated pathway to include children aged 5-9.
- Removed references to MSG203, which contained outdated guidance regarding isolation and references to the Delta variant.

## 2021-11-09

### Changed

- Updated intro and endcap message with pediatric vaccine recommendation to people 5 years and older.

## 2021-10-27

### Changed

 - Updated bot to refer to "Pfizer-BioNTech" and "Johnson & Johnson's Janssen".
 - Added message T50 about flu season to all symptomatic endpoints.
- Updated international scenarios to show regular messages and to also include MSG11.
- Updated international scenarios to remove the use of T2.
- Updated note in Q36, Q37, Q36-PED, Q37-PED, Q43 and Q44 to say, "ethnic and racial".
- Updated life-threatening symptoms in Q1, Q1-PED and Q52.
- Updated Q6, Q25, Q6-PED and Q25-PED to remove “– excluding people who have had COVID-19 within the past 3 months”.
- Updated Q8, Q11, Q15, Q18, Q21, Q26, Q47, Q50, Q205 and Q211 to say “housing at an institution of higher education”
- Updated comorbidities list for Q10, Q13, Q17, Q20, Q23, Q10-PED, Q13-PED, Q17-PED, Q20-PED, Q49.
- Updated Q201 to say, “your most recent test”.
- Updated symptoms list for Q203 and Q209.
- Added Q53 to ask about testing status.
- Expanded Vaccinated pathways to account for testing status.
- Updated MSG11 to say, “Guidance provided is meant for U.S. and U.S. territory based users. Non-U.S. based users should check with their relevant public health agency in country (e.g., Ministry of Health, National Centers for Disease Control, sub-national public health offices) for additional information and guidelines about COVID-19 in their location.”
- Fixed links that go state DOH sites for MH, MD, PR and WA.
- Fixed issue with asymptomatic pathway not going back to wrapper.
- Fixed issue with asymptomatic pathway not showing link to state DOH sites.

## 2021-08-16

### Changed

 - Updated messages in vaccinated pathway to match CDC's lates masking guidance

## 2021-08-03

### Changed

 - Updated intro and endcap messages to match CDC's latest masking guidance
 - Consilidated outcome of pediatric core pathway
 - Added optional user experience questions to the end paths of all flows

## 2021-07-01

### Changed

-	Added a question about vaccine status and related recommendations for persons who may be experiencing COVID-19 symptoms or may have been exposed to COVID-19 after being fully vaccinated. 
- Updated COVID-19 symptoms to include fatigue and nausea for adults and nausea for peds
-	Expanded the definition used for dyspnea 
-	Revised symptoms question to include a 10-day timeframe
-	Revised Care Message 28 and added Care Message 217 to reflect the latest testing guidance for negative results
-	Removed T50 (recommends being evaluated for influenza during flu season, December-May) from all symptomatic endpoint
-	Modified the wording of Q31 and Q38


## 2021-06-01

### Changed

- Updated intro and endcap messages to align with current guidance for fully vaccinated people
- Minor logic updates following a review of content
- Updated the definition used for pregnancy
- Revised answer choices in Q38


## 2021-04-19

### Changed

Summary of changes:
- Updated intro and endcap messages to include a recommendation to get a COVID-19 vaccine
- Introduced new questions and care recommendations that address the short and long-term effects of COVID-19 and potential reinfection
-	Expanded testing scenarios to account for testing within 10 days to 1 year
-	Revised Care Messages 27, 28, and 30 to account for longer isolation periods for those with a weakened immune system
-	Removed “vaping” from the medical conditions list


## 2021-04-05

### Changed

Summary of changes: 
- Reporting index bug-fixes
    -Corrected a missing index (headache) in the covid symptoms and adjusted pediatric symptom and comorbidity index lookups.
- Updated [Customization Wiki](https://github.com/CDCgov/covid19healthbot/wiki) to point out that only the reporting indexes in the Outcome blocks should be used for reporting.
- updated version number in bot files to "66.3" and "66.3-ne" for english and non-english bot-files respectively.

## 2021-03-02

### Changed

Summary of changes:
-	Simplified care and testing recommendation that highlight the most important information users need about COVID-19 care, risk, precautions, and testing.
-	Introduced a new header at the top of the tool and a new endcap message that provides one clear reminder for users to do their part to reduce transmission and protect themselves by wearing a mask, washing hands often, and physically distancing of at least 6 feet.   
-	Removed all third-person pronouns and instead only use the impersonal you for addressing the user. 
-	Moved all CDC hyperlinks from being embedded text within each outcome message to the end of the assessment to ensure links are easily identifiable and easy to return to later.   
-	Added a recommendation to isolate for 10 days until symptoms resolve in Care Message 28 (negative test result).
-	Added a clause in the intro message for how to respond if answering for someone else 
-	Updated logic following "only other symptoms" in Q7 and Q14. Applied current testing-based advice from version 64. 
-	Classified rash as "new" in the pediatric list of symptoms


## 2021-02-02

### Changed

- Updated testing and care advice for pediatric individuals (Age 2 to 17 years) with primary and secondary symptoms of COVID-19
- Updated demographic questions: 
 - Added new question on ZIP code
 - Added two questions on race and ethnicity
 - Revised gender identity question to be more inclusive 
 - Added Down syndrome to the list of COVID-19 high-risk conditions for adults and children


## 2020-12-23

### Changed

- Removed questions 32 and 33 on symptom severity

## 2020-12-17

### Changed

- Reintroduced headache (secondary symptom) in the list of COVID-19 adult symptoms
-	Added a new care message for influenza considerations for symptomatic adults and children
-	Updated the question about exposure with a broader definition of close contact
-	Updated options to reduce quarantine for contacts of persons with SARS-CoV-2 for asymptomatic individuals

## 2020-12-10

### Changed

-	Added a new question about testing status and results
-	Added new care messages that correspond with testing status and results
-	Added a new question about symptom severity
-	Added a new care message for individuals who have been in close contact with someone with confirmed COVID-19
-	Updated the 15 minute rule for close contact with COVID-19
-	Revised Care Messages #5, #8, and #9 to include recommendations on safe practices like washing hands with soap and water
-	Revised Care Message #6 to include additional information for healthcare workers
-	Modified testing messages to recommend testing for asymptomatic individuals who have been exposed to COVID-19


## 2020-09-10
 
### Changed

-	Added pediatric flow for ages 2 to 17 years
-	Includes specific questions for pediatric age groups and settings
- Updated COVID-19 testing and care messages and logic
-	Plain language updates


## 2020-07-15
### Changed

· Updated underlying conditions that increase risk of severe COVID-19 illness.

## 2020-06-08
### Changed
- Updated COVID-19 testing message to include HHS website to locate nearby testing centers.


## 2020-06-05
### Changed
- Removed pediatric flow <18 years old
- Updated exposure question to remove "area where COVID is widespread"
- Updated symptoms question
- Updated COVID-19 testing messages and logic 
- Plain language updates, streamlined decision tree and updated care messages
- Consolidated questions for life threating emergency


## 2020-05-13
### Changed
- Age question answer options are now shown as a dropdown list instead of individual buttons
- If user fails to answer US State question 3x, show message 0 and stop scenario

## 2020-05-08
### Changed
- Updated both non-English scenarios, wrapper and core, to version 58 (latest version)
- Updated localization string spreadsheet to include strings for non-English languages for version 58

## 2020-05-06
### Changed
- Removed custom scenario localization and switched to using Microsoft Health Bot built-in localization tool

### Added
- Localization strings spreadsheet to import into health bot instance for all scenarios

## 2020-05-01
### Changed
- Update to symptoms logic

## 2020-05-01
### Added
Algorithm:
  - Asymptomatic flow 
    - Includes a specific question on healthcare worker use of personal protective equipment
    - New care messages for this flow
  - Question on the quality of the users’ breathing 
  - Messages with information about COVID-19 testing 
  - Age stratification (≥64 and 65+) on care messages
  
Scenarios:
  - Data dictionary and consistent indexing for answer choices
  - Added an "Outcome" block for each path that sends a custom log event with the answers for each question and the corresponding index from the data dictionary

### Changed
Algorithm: 
  -	Consolidated care messages related to seeking immediate medical attention: call 911; go to the emergency department 
  - Updated symptom-related questions 
  -	Updated care messages

Scenarios:
  - Split English and Non-English into two separate scenarios for both the wrapper and core scenario

### Fixed
- State health department website links for Virginia, Rhode Island and Arkansas

## 2020-04-10
### Changed
- Updated localization strings for Chinese, Korean, Spanish and Vietnamese in Core protocol scenario and wrapper scenario

## 2020-04-07
### Added
- "ES-ES" switch statement for localization for Spanish language in Core protocol scenario and wrapper scenario

### Changed
- Change "you (they)" to "you" in location questions in wrapper scenario
- Change "Bluish lips or face" to "Blue-colored lips or face" in wrapper scenario and Core protocol scenario messages

## 2020-04-06
### Added
- Add missing 'Outcome 10' step in non-exposure pathway in Core protocol scenario

### Fixed
- Fix issue in comorbidity checking in exposure pathway in Core protocol scenario that didn't account for whether 'Pregnancy' was listed as an option
- Fix issue in comorbidity checking in non-exposure pathway in Core protocol scenario that used string instead of index of condition

## 2020-04-02
### Added
- Global conversation variable that allows accessing the Core protocol scenario outcome and questions answers in the wrapper scenario

### Changed
- Updates to localization strings in both Core protocol scenario and wrapper scenario

### Fixed
- Fix issue in Core protocol where selecting age: '2-4 years' and "Not experiencing life-threatening symptoms" resulted in an incorrect message outcome

## 2020-03-30
### Added
- Split scenario into two:
  - CDC wrapper scenario, which includes CDC specific questions
  - Core COVID-19 triage protocol scenario
- Split scenario includes initial localization strings for Chinese, Korean, Spanish and Vietnamese
  
### Changed
- All JavaScript expressions that were using a string for checking in scenario blocks, now use index in order to work with localization

### Removed
- Combined wrapper and core scenario

## 2020-03-28
### Changed
- Added logic: if a user fails to answer a question 3 times, show message and ask them to choose an option and restart the self-checker. This applies to all questions with a "Submit" button
- Update comorbidity language (uses algorithm version 51)
- Update decision tree logic (uses algorithm version 51)

## 2020-03-27
### Fixed
- Show 'Pregnancy' in list of comorbidity symptoms for 'Other' gender

## 2020-03-26
### Added
- Initial commit of scenario
