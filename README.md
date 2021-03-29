# CDC COVID-19 Health Bot

***

## Overview

This project collects automated screening protocols and self-checker algorithms from organizations implementing [CDC screening protocols](https://www.cdc.gov/coronavirus/2019-ncov/index.html) in interactive web sites, chat bots, and other technology.

Use of these algorithms and associated files does not imply a CDC endorsement of any one particular product, service or enterprise. U.S. Government logos, including the CDC logo, cannot be used without express, written permission. These algorithms were designed based on the best available science and should not be modified or altered. Use of these algorithms must be accompanied by the following disclaimer and non-endorsement language:

```This COVID-19 self-checker algorithm was originally developed by CDC for use as an interactive “bot” experience. CDC does not guarantee the accuracy of any non-U.S. Government version(s) of a COVID-19 self-checker algorithm. The U.S. Government does not make any warranty of any kind, either expressed or implied, for any non-U.S. Government version of the COVID-19 self-checker algorithm . Use by a non-U.S. Government organization or enterprise does not imply a U.S. Government endorsement of any one particular product, service, or enterprise or that this use of the COVID-19 self-checker algorithm represents the official views of the U.S. Government.```

**Click on the Watch button above to subscribe to updates**

## List of Screening Protocols

This list is subject to change. Pull requests are welcome from organizations with additional tools implementing CDC protocols that may be useful to capture here:

* COVID-19 Protocol - protocol used with [CDC Coronavirus Self-Checker](https://www.cdc.gov/coronavirus/2019-ncov/symptoms-testing/symptoms.html). There are 6 scenarios - 2 wrappers and 4 core protocols, and 1 string table. The latest scenarios should only be used in English. The Non-English language scenarios contain the most update to date translations available, which might not be the most update to date algorithm version. As we receive translations for the latest algorithm version, the Non-English scenarios will be updated. 
  * Latest Scenarios in English
    * [COVID-19 Core Adult Protocol](./screening_protocols/latest/covid_19_core_protocol.json) - definition file for the adult core COVID-19 protocol latest version in English
    * [COVID-19 Core Pediatric Protocol](./screening_protocols/latest/covid_19_core_pediatric_protocol.json) - definition file for the pediatric core COVID-19 protocol latest version in English
    * [COVID-19 CDC Wrapper](./screening_protocols/latest/covid_19_cdc_wrapper.json) - definition file for the CDC specific questions, including disclaimer and US location for the latest version in English
    * [COVID-19 Content and Messages](./screening_protocols/latest/covid_19_protocol_content_and_messages.pdf) - provides all content in the latest online tool for English. Includes all questions, logic, and provided messages. 
    * [COVID-19 Algorithm](./screening_protocols/latest/covid_19_protocol_algorithm.pdf) - provides a flowchart / logic diagram of the tool for the latest English scenarios.
  * Non-English Scenarios
    * [COVID-19 Core Adult Protocol Non-English](././screening_protocols/non-english/covid_19_core_protocol_non-english.json) - definition file for the adult core COVID-19 protocol latest version in English
    * [COVID-19 Core Pediatric Protocol Non-English](./screening_protocols/non-english/covid_19_core_pediatric_protocol_non-english.json) - definition file for the pediatric core COVID-19 protocol latest version in English
    * [COVID-19 CDC Wrapper Non-English](./screening_protocols/non-english/covid_19_cdc_wrapper_non-english.json) - definition file for the CDC specific questions, including disclaimer and US location for the latest version in other languages
    * [COVID-19 Content and Messages](./screening_protocols/non-english/covid_19_protocol_content_and_messages_non-english.pdf) - provides all content in the latest online tool for other languages. Includes all questions, logic, and provided messages. 
    * [COVID-19 Algorithm](./screening_protocols/non-english/covid_19_protocol_algorithm_non-english.pdf) - provides a flowchart / logic diagram of the tool for the other languages scenarios.
  * [Localization Strings](./screening_protocols/localization-custom-strings.xlsx) - this contains the localization string table that should be imported into your health bot instance. It contains strings for both English and Non-English scenarios. This file **must** be imported for the health bot to function properly. Please use [this reference](https://docs.microsoft.com/en-us/healthbot/localization) for more information on importing the file. 
  * [Customizing the Self-Checker](https://github.com/CDCgov/covid19healthbot/wiki) - shows how to customize the outcome message in the core protocols, as well as leverage the core protocol conversation data in a wrapping scenario
* [COVID-19 Screening Protocol](./screening_protocols/covid_19_screening_protocol_cdc_apple.pdf) - visual description of the protocol used for [coronavirus.gov screening tool](https://www.coronavirus.gov/).

## Public Domain Standard Notice

This repository constitutes a work of the United States Government and is not subject to domestic copyright protection under 17 USC § 105. This repository is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication.](https://creativecommons.org/publicdomain/zero/1.0/) All contributions to this repository will be released under the CC0 dedication. By submitting a pull request you are agreeing to comply with this waiver of copyright interest.

## License Standard Notice

This project constitutes a work of the United States Government and is not subject to domestic copyright protection under 17 USC § 105.

The project utilizes code licensed under the terms of the Apache Software License and therefore is licensed under ASL v2 or later.

This program is free software: you can redistribute it and/or modify it under the terms of the Apache Software License version 2, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the Apache Software License for more details.

You should have received a copy of the Apache Software License along with this program. If not, see <http://www.apache.org/licenses/LICENSE-2.0.html>.

## Privacy Standard Notice

This project contains only non-sensitive, publicly available data and information. All material and community participation is covered by the PHIResearchLab.org [Disclaimer](http://www.phiresearchlab.org/index.php?option=com_content&view=article&id=26&Itemid=15) and [Code of Conduct](http://www.phiresearchlab.org/index.php?option=com_content&view=article&id=27&Itemid=19). For more information about CDC's privacy policy, please visit <http://www.cdc.gov/privacy.html>.

## Contributing Standard Notice

Anyone is encouraged to contribute to the repository by [forking](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and submitting a pull request. (If you are new to GitHub, you might start with a [basic tutorial](https://help.github.com/en/github/getting-started-with-github/set-up-git).) By contributing to this project, you grant a world-wide, royalty-free, perpetual, irrevocable, non-exclusive, transferable license to all users under the terms of the [Apache Software License v2](http://www.apache.org/licenses/LICENSE-2.0.html) or later.

All comments, messages, pull requests, and other submissions received through CDC including this GitHub page may be subject to applicable federal law, including but not limited to the Federal Records Act and may be archived. Learn more at <http://www.cdc.gov/other/privacy.html>.

## Records Management Standard Notice

This repository is not a source of government records, but is a copy to increase collaboration and collaborative potential. All government records will be published through the [CDC web site.](http://www.cdc.gov)

## Additional Standard Notices

Please refer to [CDC's Template Repository](https://github.com/CDCgov/template/blob/master/open_practices.md) for more information about [contributing to this repository, public domain notices and disclaimers](https://github.com/CDCgov/template/blob/master/open_practices.md), and [code of conduct.](https://github.com/CDCgov/template/blob/master/code-of-conduct.md)

## Learn more about CDC GitHub Practices for Open Source Projects

<https://github.com/CDCgov/template/blob/master/open_practices.md>

**General disclaimer** This repository was created for use by CDC programs to collaborate on public health related projects in support of the [CDC mission](https://github.com/CDCgov/template/blob/master/open_practices.md). Github is not hosted by the CDC, but is a third party website used by CDC and its partners to share information and collaborate on software. CDC’s use of GitHub does not imply an endorsement of any one particular service, product, or enterprise.
