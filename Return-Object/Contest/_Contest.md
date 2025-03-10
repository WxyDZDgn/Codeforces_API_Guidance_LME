
%Contest

；2025/3/10 19:11:53


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...




[](@Contest)


Represents a contest on Codeforces.
|Field|Description|
|:--|:--|
|id |Integer.|
|name |String. Localized.|
|type |Enum: CF, IOI, ICPC. Scoring system used for the contest.|
|phase |Enum: BEFORE, CODING, PENDING_SYSTEM_TEST, SYSTEM_TEST, FINISHED.|
|frozen |Boolean. If true, then the ranklist for the contest is frozen and shows only submissions, created before freeze.|
|durationSeconds |Integer. Duration of the contest in seconds.|
|freezeDurationSeconds |Integer. Can be absent. The ranklist freeze duration of the contest in seconds if any.|
|startTimeSeconds |Integer. Can be absent. Contest start time in unix format.|
|relativeTimeSeconds |Integer. Can be absent. Number of seconds, passed after the start of the contest. Can be negative.|
|preparedBy |String. Can be absent. Handle of the user, how created the contest.|
|websiteUrl |String. Can be absent. URL for contest-related website.|
|description |String. Localized. Can be absent.|
|difficulty |Integer. Can be absent. From 1 to 5. Larger number means more difficult problems.|
|kind |String. Localized. Can be absent. Human-readable type of the contest from the following categories: Official ICPC Contest, Official School Contest, Opencup Contest, School/University/City/Region Championship, Training Camp Contest, Official International Personal Contest, Training Contest.|
|icpcRegion |String. Localized. Can be absent. Name of the Region for official ICPC contests.|
|country |String. Localized. Can be absent.|
|city |String. Localized. Can be absent.|
|season |String. Can be absent.|





/*SubLinksList*/



