
%contest.status

；2025/3/10 19:09:16


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...



Returns submissions for specified contest. Optionally can return submissions of specified user.
|Parameter|Description|
|:--|:--|
|**contestId** (Required)|Id of the contest. It is **not** the round number. It can be seen in contest URL. For example: [/contest/566/status](https://codeforces.com/contest/566/status)|
|**asManager**|Boolean. If set to true, the response will contain information available to contest managers. Otherwise, the response will contain only the information available to the participants. You must be a contest manager to use it.|
|**handle**|Codeforces user handle.|
|**from**|1-based index of the first submission to return.|
|**count**|Number of returned submissions.|

**Return value**: Returns a list of <:Submission:> objects, sorted in decreasing order of submission id.

**Example**: https://codeforces.com/api/contest.status?contestId=566&asManager=true&from=1&count=10 





/*SubLinksList*/



