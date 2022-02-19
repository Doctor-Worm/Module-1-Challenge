# Code Refactor Starter Code
<-- Updates Made by Skylar Jackson -->
- Made "Search Engine Optimization" nav link, actualy link down to corresponding box.
- Updated title of website to be "Horiseon"
- changed header "div" element to <header>
- removed unnecessary class="header" from header. Adjusted the selectors in style.css for it.
- renamed nav "div" to <nav> and adjusted selectors in style.css for it.
- added comments and added space between sections to both index and css sheets for clarification when reading code
- updated hero and content divs to be <section>
- updated conent boxes to be <article>, not div.
- added alts to images in content boxes
- added empty alts to images in right side benefits box, since they weren't important for accessibility.
- consolidated multiple classes in content boxes that all had same css styles to one single class="content-article"
- 


---> User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines


---> Acceptance Criteria
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



---> Follow these steps to complete the challenge:

Clone your starter code (Links to an external site.).

Refactor the code to meet the Acceptance Criteria.

Make sure your work meets the full list of grading requirements.

Follow the instructions to submit your Challenge for review.



---> Grading Requirements
This challenge is graded based on the following criteria:

---> Technical Acceptance Criteria: 40%
Satisfies all of the preceding acceptance criteria plus the following code improvements:

Application's links all function correctly.

Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

Application's CSS file is properly commented.



---> Deployment: 32%
Application deployed at live URL.

Application loads with no errors.

Application GitHub URL submitted.

GitHub repository that contains application code.



---> Application Quality: 15%
Application resembles (at least 90%) screenshots provided in challenge instructions.



---> Repository Quality: 13%
Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains quality README file with description, screenshot, and link to deployed application.