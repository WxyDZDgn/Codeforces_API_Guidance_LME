
%Hack

；2025/3/10 19:12:39


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...




[](@Hack)


Represents a hack, made during Codeforces Round.
|Field|Description|
|:--|:--|
|id |Integer.|
|creationTimeSeconds |Integer. Hack creation time in unix format.|
|hacker |<:Party:> object.|
|defender |<:Party:> object.|
|verdict |Enum: HACK_SUCCESSFUL, HACK_UNSUCCESSFUL, INVALID_INPUT, GENERATOR_INCOMPILABLE, GENERATOR_CRASHED, IGNORED, TESTING, OTHER. Can be absent.|
|problem |<:Problem:> object. Hacked problem.|
|test |String. Can be absent.|
|judgeProtocol |Object with three fields: "manual", "protocol" and "verdict". Field manual can have values "true" and "false". If manual is "true" then test for the hack was entered manually. Fields "protocol" and "verdict" contain human-readable description of judge protocol and hack verdict. Localized. Can be absent.|





/*SubLinksList*/



