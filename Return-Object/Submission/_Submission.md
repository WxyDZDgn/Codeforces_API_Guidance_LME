
%Submission

；2025/3/10 19:12:31


[ 导航链接列表

/*Nav*/

]

；TODO：请在此处编辑内容...




[](@Submission)


Represents a submission.
|Field|Description|
|:--|:--|
|id |Integer.|
|contestId |Integer. Can be absent.|
|creationTimeSeconds |Integer. Time, when submission was created, in unix-format.|
|relativeTimeSeconds |Integer. Number of seconds, passed after the start of the contest (or a virtual start for virtual parties), before the submission.|
|problem |<:Problem:> object.|
|author |<:Party:> object.|
|programmingLanguage |String.|
|verdict |Enum: FAILED, OK, PARTIAL, COMPILATION_ERROR, RUNTIME_ERROR, WRONG_ANSWER, WRONG_ANSWER, TIME_LIMIT_EXCEEDED, MEMORY_LIMIT_EXCEEDED, IDLENESS_LIMIT_EXCEEDED, SECURITY_VIOLATED, CRASHED, INPUT_PREPARATION_CRASHED, CHALLENGED, SKIPPED, TESTING, REJECTED. Can be absent.|
|testset |Enum: SAMPLES, PRETESTS, TESTS, CHALLENGES, TESTS1, ..., TESTS10. Testset used for judging the submission.|
|passedTestCount |Integer. Number of passed tests.|
|timeConsumedMillis |Integer. Maximum time in milliseconds, consumed by solution for one test.|
|memoryConsumedBytes |Integer. Maximum memory in bytes, consumed by solution for one test.|
|points |Floating point number. Can be absent. Number of scored points for IOI-like contests.|





/*SubLinksList*/



