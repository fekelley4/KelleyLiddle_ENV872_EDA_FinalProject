# KelleyLiddle_ENV872_EDA_FinalProject
EDA Fall 2023 final project for Fiona Kelley &amp; David Liddle. 





| Column Name           | Description                                                            | Data Type          | Units                  |
|-----------------------|------------------------------------------------------------------------|--------------------|------------------------|
| SurveyID              | The unique identifier assigned to each survey conducted in the study.  | Integer            | N/A                    |
| SurveyDate            | The date on which the survey was conducted, providing a temporal reference for the data collected. | Date               | YYYY-MM-DD             |
| StartTime             | The specific time at which the survey commenced, aiding in the temporal organization of the data. | Time               | HH:MM:SS               |
| StopTime              | The time when the survey concluded, marking the end of data collection for a particular instance. | Time               | HH:MM:SS               |
| WRIA                  | The code representing the Water Resource Inventory Area associated with the survey location. | String             | N/A                    |
| StreamCatalogCode     | A distinctive code used to catalog and categorize the surveyed stream within the dataset. | String             | N/A                    |
| StreamName            | The name assigned to the surveyed stream, offering a recognizable label for reference. | String             | N/A                    |
| LLID                  | A unique identifier associated with the stream, aiding in database management and linkage. | Integer            | N/A                    |
| Tributary To          | Information specifying the stream to which the surveyed location serves as a tributary. | String             | N/A                    |
| UpperLatitude        | The geographical coordinate indicating the northern latitude of the upper survey location. | Float              | Decimal Degrees        |
| UpperLongitude       | The geographical coordinate specifying the western longitude of the upper survey location. | Float              | Decimal Degrees        |
| LowerLatitude        | The geographical coordinate representing the southern latitude of the lower survey location. | Float              | Decimal Degrees        |
| LowerLongitude       | The geographical coordinate indicating the eastern longitude of the lower survey location. | Float              | Decimal Degrees        |
| ReachDescription      | A textual description detailing the characteristics and features of the surveyed stream reach. | Text               | N/A                    |
| DataSource            | Information indicating the source from which the survey data was obtained. | String             | N/A                    |
| Observers             | The individuals or entities responsible for conducting and overseeing the survey. | String             | N/A                    |
| SurveyMethod          | The methodology employed during the survey for data collection and assessment. | String             | N/A                    |
| Weather               | Details regarding the prevailing weather conditions at the time of the survey. | String             | N/A                    |
| StreamFlow            | Information on the flow characteristics of the surveyed stream, contributing to the understanding of hydrological conditions. | String             | N/A                    |
| FlowCFS               | The specific volume of stream flow measured in cubic feet per second, providing quantitative data on water flow. | Float              | Cubic Feet per Second  |
| StreamVisibility      | An assessment of the clarity or visibility of the surveyed stream. | String             | N/A                    |
| StreamVisibilityFeet  | The measurement, in feet, of the visibility within the surveyed stream, offering a quantitative assessment. | Float              | Feet                   |
| WaterTempFarenheit    | The temperature of the stream water measured in Fahrenheit during the survey. | Float              | Degrees Fahrenheit      |
| SurveyComment         | Additional comments or notes pertaining to specific observations or conditions made during the survey. | Text               | N/A                    |
| SurveyType            | The categorization or type of survey conducted, providing context to the nature of the data collected. | String             | N/A                    |
| SpeciesAbbr           | Abbreviations representing the species observed or studied during the survey. | String             | N/A                    |
| Species               | The full names of the species observed or studied during the survey. | String             | N/A                    |
| Run                   | Information on the specific run or migration phase of the observed fish species. | String             | N/A                    |
| RunYear               | The year in which the observed fish species participated in their migration run. | Integer            | N/A                    |
| Origin                | Details regarding the origin or source of the observed fish species. | String             | N/A                    |
| EstimatedPctSeen     | An estimation of the percentage of the fish population observed during the survey. | Float              | Percentage             |
| CWTDetectionMethod    | The method employed for detecting the presence of Coded Wire Tags (CWT) on the observed fish. | String             | N/A                    |
| DeadAdultUnknownSex   | The number of deceased adult fish of unknown gender observed during the survey. | Integer            | N/A                    |
| DeadPreviouslySampled | The number of deceased fish that were previously sampled during earlier surveys. | Integer            | N/A                    |
| SpeciesComment        | Additional comments or notes specific to the observed fish species. | Text               | N/A                    |
| AdiposeClip_CWTBeep             | The numeric count of fish with adipose fins that have coded wire tags, emitting a beeping signal.                  | Integer            | N/A                    |
| AdiposeClip_NoCWTBeep           | The numeric count of fish with adipose fins lacking coded wire tags, emitting a beeping signal.                     | Integer            | N/A                    |
| AdiposeClip_NoHead              | The numeric count of fish with adipose fins and no head, indicating a specific characteristic during observation. | Integer            | N/A                    |
| NoAdiposeClip_CWTBeep           | The numeric count of fish without adipose fins that have coded wire tags, emitting a beeping signal.               | Integer            | N/A                    |
| NoAdiposeClip_NoCWTBeep         | The numeric count of fish without adipose fins and lacking coded wire tags, emitting a beeping signal.              | Integer            | N/A                    |
| NoAdiposeClip_NoHead            | The numeric count of fish without adipose fins and no head, denoting a distinctive observation.                    | Integer            | N/A                    |
| AdiposeClipUnknown_CWTBeep      | The numeric count of fish with an unknown status of adipose fins that have coded wire tags, emitting a beeping signal. | Integer            | N/A                    |
| AdiposeClipUnknown_NoCWTBeep    | The numeric count of fish with an unknown status of adipose fins lacking coded wire tags, emitting a beeping signal. | Integer            | N/A                    |
| AdiposeClipUnknown_NoHead       | The numeric count of fish with an unknown status of adipose fins and no head, representing a specific observation during the survey. | Integer            | N/A                    |
