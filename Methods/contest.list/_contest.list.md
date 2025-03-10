
%contest.list

；2025/3/10 19:08:41


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...



Returns information about all available contests.
|Parameter|Description|
|:--|:--|
|**gym**|Boolean. If true — than gym contests are returned. Otherwide, regular contests are returned.|
|**groupCode**|Group code (e.g., `sfSJn5pz1a`) is used to filter contests. You need to log in with an account that has at least read access to the group.|

**Return value**: Returns a list of <:Contest:> objects. If this method is called not anonymously, then all available contests for a calling user will be returned too, including mashups and private gyms.

**Example**: https://codeforces.com/api/contest.list?gym=true 





/*SubLinksList*/



