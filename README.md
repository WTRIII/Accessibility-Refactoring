# Accessibility
A marketing company requested a refactor of their existing website. The company requested the following criteria: 

- semantic HTML elements
- logical structure of HTML elements
- alt attributes for images and logos
- sequential ordering of header elements
- concise, descriptive title
- application links function correctly
- CSS selectors and properties are consolidated and organized to follow semantic structure
- application CSS file is properly commented

## All requests were implemented. Summary to follow:

- removed all div elements and replaced with semantic terminology
- added navigation bar and moved links to the bar
- updated headers to fall in sequential order while still maintaining original site settings
- CSS stylesheet updated to reflect changes in HTML
### - Comments were added to CSS as notes on efficiency of classes. Changes were not made in case of company policy or procedure regarding coding practices.
- CSS stylesheet reordered and placed into sections with comments to indicate settings which control various functions of the website

## Image of website after implementation of changes:
![Horiseon Webpage](assets/images/Horiseon-Webpage-Updated.png)

# Original User Story

AS A marketing agency I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the homework instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.
