# TutorialHelper
Helper module to easily create an info button for each page to highlight sections of the page and support with explanatory text.

== Description ==

Helper module to easily create an info button for each page to highlight sections of the page and support with explanatory text

== Typical usage scenario ==

This module can be used for every page to highlight sections.

== Features and limitations ==
- Every container within a page can be highlighted by adding a specific class name ('mx-tutorial-#sectionname’)
- It is not possible to highlight sections across containers 

== Dependencies ==
- Atlas Core
- CommitScopeFeedback (available in Marketplace)
- Mx 9.6.9 or higher
- _tutorial.scss need to be added to the styling (included by the module in the resources folder

== Installation ==
- Add the styling code found in Resources/Tutorial/_tutorial.scss to your styling

== Configuration ==

=== In Studio Pro ===
- Add the module roles to your security (Administrator to your admin role and User to all the other roles)
- Add Tutorial_Configuration to your navigation
- Add the Snippet_Tutorial_Buttons to a page of your choosing
- Add to the section you want to highlight a container with the class 'mx-tutorial-#sectionname' (without the quote characters). See Tutorial_Example for an example.

=== Runtime ===
- As an Admin go to the page and click on 'Admin - Get tutorial steps'
- As an Admin, add text to the steps per page
- [Optional] Use export/import to reuse all the pages and steps
