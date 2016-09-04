Create a smart REST client that will be able to connect to a correctly set up REST server, display forms for all of the defined endpoints, provide ability to edit JSON before submitting it, display responses possibly side-by-side with examples provided, has a theme support, will be able to provide guidance to server's creator on how to correctly set it up.

## Use Case Scenario 1
User inputs a URL to the REST server, possibly inputs different base URL
System fetches definition from server
And displays a list of discovered resources
- Optionally displays health status of the server
- Optionally displays description and other cool stuff from definition

## Use Case Scenario 2
User clicks on any of the links to resources 
System directs him to a form/JSON page (kinda like swagger editor with code on the right) 
Using Schema from definition file it draws form 
- Optionally displays examples dropdown 
If user clicks "send" JSON gets sent to specified URL 
Response is displayed in the bottom of the screen 
- Optionally with HATEOAS links 
- Optionally side-by-side diff with example? Normalize JSON option? 

## Non-functional requirements
Theme-able
Angular2 app with components
Electron app
Ability to "style" resulting forms server-side using jsonform library

## Plan
Investigate swagger editor and how it does what it does
Replicate step 2 form - add response part, which can be mocked for now
Research any JSON diff libs
Try to use this page with swagger public example (pet store?)
Verify that everything works, but **don't go overboard with testing**, keep scenarios in mind.
Try to package it with Electron.
Find out about auto-update functionality (github-based?)
Review the plan, come up with new one  

    New ideas/suggestions/tasks for the plan go after this line
   
 start here...

