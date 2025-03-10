
%Authorization

；2025/3/10 19:07:39


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...



All methods can be requested anonymously. This way only public data will be accessable via API. To access data, private for some user (e.g. hacks during the contest), API key must be generated on https://codeforces.com/settings/api page. Each API key has two parameters: `key` and `secret`. To use the key you must add following parameters to your request.

1. `apiKey` — it must be equal to `key`
2. `time` — current time in unix format (e.g., System.currentTimeMillis()/1000). If the difference between server time and time, specified in parameter, will be greater than 5 minutes, request will be denied.
3. `apiSig` — signature to ensure that you know both `key` and `secret`. First six characters of the `apiSig` parameter can be arbitrary. We recommend to choose them at random for each request. Let's denote them as `rand`. The rest of the parameter is hexadecimal representation of SHA-512 hash-code of the following string: `<rand>/<methodName>?param1=value1&param2=value2...&paramN=valueN#<secret>` where `(param_1, value_1), (param_2, value_2),..., (param_n, value_n)` are all the request parameters (including `apiKey`, `time`, but excluding `apiSig`) with corresponding values, sorted lexicographically first by `param_i`, then by `value_i`.

For example:

If your `key` is `xxx`, `secret` is `yyy`, chosen `rand` is `123456` and you want to access method `contest.hacks` for contest 566, you should compose request like this: `https://codeforces.com/api/contest.hacks?contestId=566&apiKey=xxx&time=1741526578&apiSig=123456<hash>`, where `<hash>` is `sha512Hex(123456/contest.hacks?apiKey=xxx&contestId=566&time=1741526578#yyy)`





/*SubLinksList*/



