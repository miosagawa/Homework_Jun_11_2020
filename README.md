Folder update content:
Update date：June 11, 2020
Update content：

1.html file debugging
UTA-AUS-FSF-FT-06-2020-U-C/01-Class-Content/01-HTML-Git-CSS/02-Homework/Develop/index.html

    1-1.added comments

    1-2.Modification place（3 places）：

        １．Add id attribute
        <div class="search-engine-optimization">
        ↓
        <div id="search-engine-optimization" class="search-engine-optimization">

        ２．Delete end tag
        <img src="./assets/images/cost-management.png"></img>
        ↓
        <img src="./assets/images/cost-management.png" />  

        ３．Partial correction of headline characters
        <h1>Hori<span class=“se”>zo</span>n</h1>
        ↓
        <h1>Hori<span class="zo">zo</span>n</h1>
        （※Check points：Did you intentionally mistake in the spelling?）

２.other homework
* The URL of the deployed application.
https://miosagawa.github.io/Homework_Jun_11_2020/Jun_11_2020/index.html


* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.
https://github.com/miosagawa/Homework_Jun_11_2020.git





--------------------------

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.





