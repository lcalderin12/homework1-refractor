# 01 HTML CSS Git: Code Refactor

This original source code had contingencies that made the code not only difficult to follow but also more lengthy than necessary. For starters, classes were added to the divs in the html file which were then referenced in the .css. For example: ".header div ul li" was given a class of ".link-3." This compresses the code in an efficient and less confusing manner. Also there were unecessary atributes in the .css file which could of been simpified without any additional modification other than just deleting extra syntax. An example of this is the ".header h1" was simplified to "h1" which has the same effect yet more efficient. To make the .cc file more readable the attributes that were applicalbe to classes, such as ".float-left" were moved to the end of the .css file. This logic was also applied to the divs within the ".content" class. They were moved up in the .css file to be right below the ".content" class. Finally, a container was added to the body of the page so that when the window is shortened the attibutes of the page stay within the divs that they were in.

https://lcalderin12.github.io/homework1-refractor/

Luis Calderin

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
