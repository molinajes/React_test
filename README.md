# Aurora Front-end Homework Test

```Note
It was great speaking with you! As per our conversation, here's the next
step in our hiring process. Below a programming problems. Please read the descriptions
thoroughly then create a program to solve the problems.
```

## Introduce

In modern agile software development practice, there is a development practice called "Content Management System",
which requires any time, any place can manage content user generated. we want to create a product such as
Aurora Content Management that can easily manage these content the user created.

## Interface

![UI layout detail 1](https://bitbucket.org/aurorahr/frontend-homework-test/raw/6a671fbcf73fa45c0d34f23c4dbe58b4c64d0871/design/guide/Content_Management_1.png)
![UI layout detail 2](https://bitbucket.org/aurorahr/frontend-homework-test/raw/6a671fbcf73fa45c0d34f23c4dbe58b4c64d0871/design/guide/Content_Management_2.png)

## Style Guide

Please open `/design/measure/index.html` in browser and check the UI layout and style guide.

## Requirements

* README file is required.
* Resources should be displayed well when there are too many resources tags
* For POPOVER DIALOG:
    * Must implement it yourself
    * Get dismissed by clicking outside of the popover
    * When clicked `Mark All as Read`, all the unread articles should be `isRead` and number of unread articles should be 0 at the same time.
* For DELETE button:
    * When clicked the `DELETE` button, make a request and remove this item from the list
    * At the same time the number of unread articles and number of all articles should be decreased
* For MARK AS READ button:
    * When clicked the `MARK AS READ` button, make a request and change the article's read status
    * At the same time the number of unread articles should be decreased
* For backend data
    1. Use the data API which provided by us to get or change data
    2. The data API is provided by the mock server which in the attachment
    3. Please check the `mock` folder and follow the steps in README.md to run the mock server
* UI must be implemented as the design of Content Management mentioned above
* The layout should look CONSISTENTLY for IE11+, latest Chrome and Firefox.
* Tools like Webpack/Grunt/Gulp, Babel, SASS/LESS and test libraries are ALLOWED

Note:

  1. We want our hiring process to be fair, and for everyone to start from the same place. To enable this, we request that you do not share or publish these problems.
  2. We need a react developer, so please use `React` to finish the test.
  3. Nice to have Javascript Unit Test

```Note
As a general rule, we allow three days from the date that you receive
these instructions to submit your code, but you may request more time
from your recruiter if needed. If you have any questions about the code
as it relates to your interview process, please contact us.
```

We welcome your arrival if you can easily complete the homework test.
Thank you very much, good luck to you😄