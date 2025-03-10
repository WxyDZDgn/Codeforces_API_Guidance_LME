
%Party

；2025/3/10 19:12:00


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...




[](@Party)


Represents a party, participating in a contest.
|Field|Description|
|:--|:--|
|contestId |Integer. Can be absent. Id of the contest, in which party is participating.|
|members |List of <:Member:> objects. Members of the party.|
|participantType |Enum: CONTESTANT, PRACTICE, VIRTUAL, MANAGER, OUT_OF_COMPETITION.|
|teamId |Integer. Can be absent. If party is a team, then it is a unique team id. Otherwise, this field is absent.|
|teamName |String. Localized. Can be absent. If party is a team or ghost, then it is a localized name of the team. Otherwise, it is absent.|
|ghost |Boolean. If true then this party is a ghost. It participated in the contest, but not on Codeforces. For example, Andrew Stankevich Contests in Gym has ghosts of the participants from Petrozavodsk Training Camp.|
|room |Integer. Can be absent. Room of the party. If absent, then the party has no room.|
|startTimeSeconds |Integer. Can be absent. Time, when this party started a contest.|





/*SubLinksList*/



