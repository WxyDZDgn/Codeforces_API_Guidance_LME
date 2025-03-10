
%contest.standings

；2025/3/10 19:09:05


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...



Returns the description of the contest and the requested part of the standings.
|Parameter|Description|
|:--|:--|
|**contestId** (Required)|Id of the contest. It is **not** the round number. It can be seen in contest URL. For example: [/contest/566/status](https://codeforces.com/contest/566/status)|
|**asManager**|Boolean. If set to true, the response will contain information available to contest managers. Otherwise, the response will contain only the information available to the participants. You must be a contest manager to use it.|
|**from**|1-based index of the standings row to start the ranklist.|
|**count**|Number of standing rows to return.|
|**handles**|Semicolon-separated list of handles. No more than 10000 handles is accepted.|
|**room**|If specified, than only participants from this room will be shown in the result. If not — all the participants will be shown.|
|**showUnofficial**|If true than all participants (virtual, out of competition) are shown. Otherwise, only official contestants are shown.|
|**participantTypes**|Comma-separated list of participant types without spaces. Possible values: CONTESTANT, PRACTICE, VIRTUAL, MANAGER, OUT_OF_COMPETITION. Only participants with the specified types will be displayed.|

**Return value**: Returns object with three fields: "contest", "problems" and "rows". Field "contest" contains a <:Contest:> object. Field "problems" contains a list of <:Problem:> objects. Field "rows" contains a list of <:RanklistRow:> objects.

**Example**: https://codeforces.com/api/contest.standings?contestId=566&asManager=true&from=1&count=5&showUnofficial=true 





/*SubLinksList*/



