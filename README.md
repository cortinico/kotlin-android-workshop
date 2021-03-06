This repository hosts the coding exercises from a Kotlin Workshop for Android. Basic knowledge of
both Android and Java is assumed for anyone participating in this workshop. No prior knowledge of
Kotlin is required; the linked presentations, videos, and workbook start from very basic syntax
in Kotlin and build from there.

The linked presentations and videos are from a recording of a live event held internally at Yelp on
May 24th, 2018, and may already be out of date. If a new event is held, this repository and its
recordings may be updated. Otherwise, any updates are rather unlikely.

## Format of this Repository

There are a total of 7 apps in this repository. If you follow along with the workshop, you can start
from the folder `app` and build your Android app by following the instructions in the video and
workbook. If you struggle to complete an exercise, you can simply look in the folder with the
corresponding number. For example, `app4` contains the Android app that is the result of completing
exercises 1-4. Alternatively, if you’re interested in completing, for example, only sessions 3 and
6, you can start from `app2` to complete the exercises in session 3, and then start from `app5` to
complete the exercises in session 6.

## Format of the Workshop

The workshop was intended as a one-day event. It was split into sessions of about 1 hour each. Each
session roughly consisted of a 20-minute presentation, followed by a 20-minute live coding session,
and finally, a 20-minute attendee coding session on a topic relevant to the presentation.
Presenters were available during the coding sessions to answer questions or troubleshoot any issues.
By the end of the day, we built a simple app that displayed a list of businesses using Yelp's public
API.

Here’s a [workbook][workbook] with more detailed information on the topic, and below is a list of
all sessions and a brief summary of their content.

## Syllabus

1. Basic Syntax and Types - how to create classes, interfaces, and functions. At the end you should
be able to write a very simple Kotlin class ([presentation][prezi1], [video][video1])

2. Constructors and Control Flow - difference between statements and expressions, conditional
statements and loops, jumps and qualifiers, primary and secondary constructors, and execution flow
when constructing instances ([presentation][prezi2], [video][video2])

3. Functions - operators, inlining, a little bit about generics, named parameters, lambdas and
closures, obtaining references to functions and passing them to other functions, and higher-order
functions ([presentation][prezi3], [video][video3])

4. Properties and Nullability - Java interop, synthetic and delegated properties, custom setters and
getters, `lateinit`, ​nullable and non-null properties, and optional invocation
([presentation][prezi4], [video][video4])

5. Useful Kotlin Standard Functions - introduction to `use`, `let`, `apply`, `also`, `with`,
`isEmpty`, `orEmpty`, and more, as well as how and when to use them ([presentation][prezi5],
[video][video5])

6. Kotlin's Collections APIs - mapping, transforming, filtering, aggregating, and associating
anything you can iterate over like a boss ([presentation][prezi6], [video][video6])

7. How to Build DSLs - what they’re useful for and how to build them ([presentation][prezi7],
[video][video7])

## Licenses

This Kotlin Workshop exercise repository is licensed under the Apache License, Version 2.0:
http://www.apache.org/licenses/LICENSE-2.0

The Kotlin Workshop presentations, videos and other written materials are licensed under the
Creative Commons, Attribute, No Derivatives, Version 3.0 US:
https://creativecommons.org/licenses/by-nd/3.0/us/legalcode

[workbook]: https://github.com/Yelp/kotlin-android-workshop/blob/master/Kotlin%20For%20Android%20-%20Workbook.pdf  "Kotlin for Android - Workbook"
[prezi1]: https://www.slideshare.net/GeshMarkov/kotlin-for-android-basics-part-1-of-7-120029125 "Kotlin for Android - Part 1 - Basics (Presentation)"
[video1]: https://www.youtube.com/embed/5Zb_jfSVSU4?rel=0 "Kotlin for Android - Part 1 - Basics (Video)"
[prezi2]: https://www.slideshare.net/GeshMarkov/kotlin-for-android-constructors-and-control-flow-part-2-of-7 "Kotlin for Android - Part 2 - Constructors and Control Flow (Presentation)"
[video2]: https://www.youtube.com/embed/ooVFB-F0wys?rel=0 "Kotlin for Android - Part 2 - Constructors and Control Flow (Video)"
[prezi3]: https://www.slideshare.net/GeshMarkov/kotlin-for-android-functions-part-3-of-7 "Kotlin for Android - Part 3 - Functions (Presentation)"
[video3]: https://www.youtube.com/embed/i233TBeASBg?rel=0 "Kotlin for Android - Part 3 - Functions (Video)"
[prezi4]: https://www.slideshare.net/GeshMarkov/kotlin-for-android-properties-part-4-of-7 "Kotlin for Android - Part 4 - Properties (Presentation)"
[video4]: https://www.youtube.com/embed/zuNWuiEjstg?rel=0 "Kotlin for Android - Part 4 - Properties (Video)"
[prezi5]: https://www.slideshare.net/GeshMarkov/kotlin-for-android-useful-kotlin-standard-functions-part-5-of-7 "Kotlin for Android - Part 5 - std-lib (Presentation)"
[video5]: https://www.youtube.com/embed/AfuCSD926ls?rel=0 "Kotlin for Android - Part 5 - std-lib (Video)"
[prezi6]: https://www.slideshare.net/GeshMarkov/kotlin-for-android-collections-apis-part-6-of-7 "Kotlin for Android - Part 6 - Collections (Presentation)"
[video6]: https://www.youtube.com/embed/y0L29iKLdL4?rel=0 "Kotlin for Android - Part 6 - Collections (Video)"
[prezi7]: https://www.slideshare.net/GeshMarkov/kotlin-for-android-how-to-build-dsls-part-7-of-7 "Kotlin for Android - Part 7 - DSLs (Presentation)"
[video7]: https://www.youtube.com/embed/ILnvVX1bxgs?rel=0 "Kotlin for Android - Part 7 - DSLs (Video)"
