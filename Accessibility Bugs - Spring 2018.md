**CS 490 - Homework**
This document was used in the fall 2017 version of CS 490 Software Engineering at Western New England University. The table may be updated as bugs are fixed or closed. 

**Bug Tracking - 20 Points**

The Mozilla Dev Tools communityhas provided us with a list of possible bugs to work on:

https://github.com/devtools-html/debugger.html/issues?q=is%3Aissue+is%3Aopen+label%3Aaccessibility

You must explore the list of bugs and fill out the table below according
to:

  - **Dependent On** - List the number of any bugs upon which the
    current bug is dependent.

  - **Related To** - List the number of any related bugs mentioned in
    the bug report.

  - **Community** - List the names of any communities that must be
    consulted when solving the bug.

  - **Hints for Solving** - Identify any hints, directions or solutions
    provided in the bug report.

  - **Status -** Select one of the status terms:
    
      - **Wait** - The solution cannot be completed until some action is
        taken by someone in the community
    
      - **Go** - The solution can be created with no further input
        needed from the community
    
      - **Question** - There are unresolved questions within the bug
        report that require answers from the
        
      - **Resolved** - The issue was either closed or the solution is no longer needed.
community

|              |                                            |                |                             |                                                                                                          |            |
| ------------ | ------------------------------------------ | -------------- | --------------------------- | -------------------------------------------------------------------------------------------------------- | ---------- |
| **Bug No.** | **Dependent On**                           | **Related To** | **Community**               | **Hints for Solving**                                                                                    | **Status** |
| devtools-html/debugger.html#4067         | devtools-html/devtools-core#695 - blocker | devtools-html/debugger.html#4081, devtools-html/debugger.html#4068     |                             | Solution might be in m-c. Jason indicated he would update #695 soon.                                    | Resolved       |
| devtools-html/debugger.html#4068         |                                            | devtools-html/debugger.html#4081           |                             | Same solution as for #4067. Requires updating to latest devtools-core tree component. See comment on devtools-html/debugger.html#4067 | Resolved       |
| devtools-html/debugger.html#4070         |                                            | devtools-html/debugger.html#4071           |                             | Example code provided                                                                                    | Berea students claimed.        |
| devtools-html/debugger.html#4071         |                                            | devtools-html/debugger.html#4070           |                             | Example code provided                                                                                    | Berea students claimed. Likley merged with devtools-html/debugger.html#5285. (Don't work on)        |
| devtools-html/debugger.html#4073         |                                            |                |                             | Explanation of solution provided by Garbee. Sample code provided.                                        | Go         |
| devtools-html/debugger.html#4075         |                                            |                |                             | Explanation of solution provided by Garbee. Sample code provided.                                        | Go , Berea students have made some progress on this. Still "Go".  |
| devtools-html/debugger.html#4076         |                                            |                | Chrome DevTools, Edge teams |                                                                                                          | Wait       |
| devtools-html/debugger.html#4078         |                                            |                | Designer                    | Is implementing the "focus ring" a short term solution? Sample code provided.                            | Resolved  |
| devtools-html/debugger.html#4080         |                                            |                |                             | Sample code provided. Some question as to what terms mean.                                               | Go   |
| devtools-html/debugger.html#4081         |                                            | devtools-html/debugger.html#4067, devtools-html/debugger.html#4068     |                             | One comment suggested closing the bug.                                                                   | Resolved       |

[jlast](https://devtools-html.slack.com/team/U3UH6CSLR#_blank)

[7:39
PM](https://devtools-html.slack.com/archives/C3VTFTCBY/p1505777957000083#_blank)

oh great. yeah, the student should provide lots of
feedback

[7:39](https://devtools-html.slack.com/archives/C3VTFTCBY/p1505777959000106#_blank)

[https://github.com/devtools-html/debugger.html/issues/4080](https://github.com/devtools-html/debugger.html/issues/4080#_blank)

![](media/image1.png) GitHub

[accordion accessibility · Issue \#4080 ·
devtools-html/debugger.html](https://github.com/devtools-html/debugger.html/issues/4080#_blank)

This issue tracks the work to make the accordion accessible. A PR can do
one or several items in the checklist: Visually (CSS focus styling)
there is no way to focus on the accordion headers and
...

![](media/image2.png)

[7:39](https://devtools-html.slack.com/archives/C3VTFTCBY/p1505777988000176#_blank)

^ I left some notes in a comment, but would love to get your thoughts /
input as
well

[7:40](https://devtools-html.slack.com/archives/C3VTFTCBY/p1505778010000195#_blank)

[@victoria](https://devtools-html.slack.com/team/U5E02H0AH#_blank) what
do you think would be a good focus state for accordion headers?
