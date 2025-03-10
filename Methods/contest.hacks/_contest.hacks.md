
%contest.hacks

；2025/3/10 19:08:33


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...



Returns list of hacks in the specified contests. Full information about hacks is available only after some time after the contest end. During the contest user can see only own hacks.
|Parameter|Description|
|:--|:--|
|**contestId** (Required)|Id of the contest. It is not the round number. It can be seen in contest URL. For example: [/contest/566/status](https://codeforces.com/contest/566/status)|
|**asManager**|Boolean. If set to true, the response will contain information available to contest managers. Otherwise, the response will contain only the information available to the participants. You must be a contest manager to use it.|

**Return value**: Returns a list of <:Hack:> objects.

**Example**: https://codeforces.com/api/contest.hacks?contestId=566&asManager=true 





/*SubLinksList*/



