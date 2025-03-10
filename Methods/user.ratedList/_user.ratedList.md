
%user.ratedList

；2025/3/10 19:10:25


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...



Returns the list users who have participated in at least one rated contest.
|Parameter|Description|
|:--|:--|
|**activeOnly**|Boolean. If true then only users, who participated in rated contest during the last month are returned. Otherwise, all users with at least one rated contest are returned.|
|**includeRetired**|Boolean. If true, the method returns all rated users, otherwise the method returns only users, that were online at last month.|
|**contestId**|Id of the contest. It is **not** the round number. It can be seen in contest URL. For example: [/contest/566/status](https://codeforces.com/contest/566/status)|

**Return value**: Returns a list of <:User:> objects, sorted in decreasing order of rating.

**Example**: https://codeforces.com/api/user.ratedList?activeOnly=true&includeRetired=false 





/*SubLinksList*/



