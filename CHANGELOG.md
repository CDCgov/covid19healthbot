# Changelog

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