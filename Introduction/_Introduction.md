
%Introduction

；2025/3/10 19:07:31


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...



With Codeforces API you can get access to some of our data in machine-readable JSON format.

To access the data you just send a HTTP-request to address `https://codeforces.com/api/{methodName}` with method-specific parameters. Each method description has an example URL.

Each method call returns a JSON-object with three possible fields: status, comment and result.

- Status is either "OK" or "FAILED".
- If status is "FAILED" then comment contains the reason why the request failed. If status is "OK", then there is no comment.
- If status is "OK" then result contains method-dependent JSON-element which will be described for each method separately. If status is "FAILED", then there is no result.

API may be requested at most 1 time per two seconds. If you send more requests, you will receive a response with "FAILED" status and "Call limit exceeded" comment.

Language-depended fields like names or descriptions will be returned in the default language. Also, you can pass additional parameter `lang` with values `en` and `ru` to select the language of the result.




/*SubLinksList*/



