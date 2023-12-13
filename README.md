# KelleyLiddle_ENV872_EDA_FinalProject
EDA Fall 2023 final project for Fiona Kelley &amp; David Liddle. 





| Column Name                     | Description                                                                                                       | Data Type          | Units                  |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------|--------------------|------------------------|
| SurveyID                        | The unique identifier assigned to each survey conducted in the study.                                             | Number             | N/A                    |
| SurveyDate                      | The date and time on which the survey was conducted, providing a temporal reference for the data collected.       | Date & Time        | YYYY-MM-DD HH:MM:SS   |
| StartTime                       | The specific time at which the survey commenced, aiding in the temporal organization of the data.                  | Plain Text         | N/A                    |
| StopTime                        | The time when the survey concluded, marking the end of data collection for a particular instance.                  | Plain Text         | N/A                    |
| WRIA                            | The code representing the Water Resource Inventory Area associated with the survey location.                      | Number             | N/A                    |
| StreamCatalogCode               | A distinctive code used to catalog and categorize the surveyed stream within the dataset.                         | Plain Text         | N/A                    |
| StreamName                      | The name assigned to the surveyed stream, offering a recognizable label for reference.                             | Plain Text         | N/A                    |
| LLID                            | A unique identifier associated with the stream, aiding in database management and linkage.                        | Plain Text         | N/A                    |
| Tributary To                    | Information specifying the stream to which the surveyed location serves as a tributary.                            | Plain Text         | N/A                    |
| UpperRiverMile                  | The mile marker indicating the upper limit of the surveyed river location.                                         | Number             | N/A                    |
| LowerRiverMile                  | The mile marker indicating the lower limit of the surveyed river location.                                         | Number             | N/A                    |
| UpperLatitude                   | The geographical coordinate indicating the northern latitude of the upper survey location.                       | Plain Text         | N/A                    |
| UpperLongitude                  | The geographical coordinate specifying the western longitude of the upper survey location.                        | Plain Text         | N/A                    |
| LowerLatitude                   | The geographical coordinate representing the southern latitude of the lower survey location.                       | Plain Text         | N/A                    |
| LowerLongitude                  | The geographical coordinate indicating the eastern longitude of the lower survey location.                        | Plain Text         | N/A                    |
| ReachDescription                | A textual description detailing the characteristics and features of the surveyed stream reach.                    | Plain Text         | N/A                    |
| DataSource                      | Information indicating the source from which the survey data was obtained.                                          | Plain Text         | N/A                    |
| Observers                       | The individuals or entities responsible for conducting and overseeing the survey.                                   | Plain Text         | N/A                    |
| SurveyMethod                    | The methodology employed during the survey for data collection and assessment.                                     | Plain Text         | N/A                    |
| Weather                         | Details regarding the prevailing weather conditions at the time of the survey.                                      | Plain Text         | N/A                    |
| StreamFlow                      | Information on the flow characteristics of the surveyed stream, contributing to the understanding of hydrological conditions. | Plain Text  | N/A                    |
| FlowCFS                         | The specific volume of stream flow measured in cubic feet per second, providing quantitative data on water flow.   | Plain Text         | Cubic Feet per Second  |
| StreamVisibility                | An assessment of the clarity or visibility of the surveyed stream.                                                    | Plain Text         | N/A                    |
| StreamVisibilityFeet            | The measurement, in feet, of the visibility within the surveyed stream, offering a quantitative assessment.         | Plain Text         | Feet                   |
| WaterTempFarenheit              | The temperature of the stream water measured in Fahrenheit during the survey.                                       | Plain Text         | Degrees Fahrenheit      |
| SurveyComment                   | Additional comments or notes pertaining to specific observations or conditions made during the survey.            | Plain Text         | N/A                    |
| SurveyDetailID                  | A unique identifier associated with detailed survey information.                                                      | Number             | N/A                    |
| SurveyType                      | The categorization or type of survey conducted, providing context to the nature of the data collected.              | Plain Text         | N/A                    |
| SpeciesAbbr                     | Abbreviations representing the species observed or studied during the survey.                                       | Plain Text         | N/A                    |
| Species                         | The full names of the species observed or studied during the survey.                                                  | Plain Text         | N/A                    |
| Run                             | Information on the specific run or migration phase of the observed fish species.                                      | Plain Text         | N/A                    |
| RunYear                         | The year in which the observed fish species participated in their migration run.                                     | Plain Text         | N/A                    |
| Origin                          | Details regarding the origin or source of the observed fish species.                                                  | Plain Text         | N/A                    |
| EstimatedPctSeen                | An estimation of the percentage of the fish population observed during the survey.                                   | Plain Text         | Percentage             |
| CWTDetectionMethod              | The method employed for detecting the presence of Coded Wire Tags (CWT) on the observed fish.                        | Plain Text         | N/A                    |
| LiveTotal                       | The total count of live fish observed during the survey.                                                              | Number             | N/A                    |
| LiveAdultMale                   | The count of live adult male fish observed during the survey.                                                         | Number             | N/A                    |
| LiveAdultFemale                 | The count of live adult female fish observed during the survey.                                                       | Number             | N/A                    |
| LiveAdultUnknownSex             | The count of live adult fish of unknown gender observed during the survey.                                            | Number             | N/A                    |
| LiveJack                        | The count of live jack fish observed during the survey.                                                               | Number             | N/A                    |
| DeadTotal                       | The total count of deceased fish observed during the survey.                                                          | Number             | N/A                    |
| DeadAdultMale                   | The count of deceased adult male fish observed during the survey.                                                     | Number             | N/A                    |
| DeadAdultFemale                 | The count of deceased adult female fish observed during the survey.                                                   | Number             | N/A                    |
| DeadAdultUnknownSex             | The count of deceased adult fish of unknown gender observed during the survey.                                        | Plain Text         | N/A                    |
| DeadJack                        | The count of deceased jack fish observed during the survey.                                                            | Number             | N/A                    |
| DeadPreviouslySampled           | The count of deceased fish that were previously sampled during earlier surveys.                                      | Number             | N/A                    |
| NewReddCount                    | The count of new redds (fish nests) observed during the survey.                                                       | Number             | N/A                    |
| PreviousReddCount               | The count of redds observed during previous surveys.                                                                  | Number             | N/A                    |
| CombinedReddCount               | The combined count of new and previous redds observed during the survey.                                              | Number             | N/A                    |
| SpeciesComment                  | Additional comments or notes specific to the observed fish species.                                                  | Plain Text         | N/A                    |
| AdiposeClip_CWTBeep             | The numeric count of fish with adipose fins that have coded wire tags, emitting a beeping signal.                  | Number             | N/A                    |
| AdiposeClip_NoCWTBeep           | The numeric count of fish with adipose fins lacking coded wire tags, emitting a beeping signal.                     | Number             | N/A                    |
| AdiposeClip_NoHead              | The numeric count of fish with adipose fins and no head, indicating a specific characteristic during observation. | Number             | N/A                    |
| NoAdiposeClip_CWTBeep           | The numeric count of fish without adipose fins that have coded wire tags, emitting a beeping signal.               | Number             | N/A                    |
| NoAdiposeClip_NoCWTBeep         | The numeric count of fish without adipose fins and lacking coded wire tags, emitting a beeping signal.              | Number             | N/A                    |
| NoAdiposeClip_NoHead            | The numeric count of fish without adipose fins and no head, denoting a distinctive observation.                    | Number             | N/A                    |
| AdiposeClipUnknown_CWTBeep      | The numeric count of fish with an unknown status of adipose fins that have coded wire tags, emitting a beeping signal. | Number             | N/A                    |
| AdiposeClipUnknown_NoCWTBeep    | The numeric count of fish with an unknown status of adipose fins lacking coded wire tags, emitting a beeping signal. | Number             | N/A                    |
| AdiposeClipUnknown_NoHead       | The numeric count of fish with an unknown status of adipose fins and no head, representing a specific observation during the survey. | Number  | N/A                    |
