---
layout: post
title:  "Website Testing"
date:   2018-01-22 19:54:37 -0800
categories: jekyll update
---


Before I begin with what is Website Testing, let’s understand the importance of testing in Web Development.
Importance of Website Testing:
Whenever a common person heard about any company/restaurant/firm, what do you think he/she will do?  

The answer is: he/she will definitely try to look for your website. And what if he/she visits your website and finds a lot of spelling mistakes or broken links? It is also possible that the user is visiting your website on a mobile device and your website doesn’t look nice. What do you think he/she will do?

Obviously, he/she will leave your website and will never return to it again.
Even if you are not the owner of a company but you want to work as a Web Developer, you need to know the importance and techniques of Website Testing.

**What is Website Testing?**
Website Testing means checking your website for potential bugs before you make it live. 

**Website Testing Checklist:**

-  Functionality Testing
-  Browser Testing
-  Usability Testing
-  Interface Testing
-  Database Testing
-  Performance Testing
-  Security Testing
-  Crowd Testing (Latest Trend)


**Functionality Testing:**
Check if the product is meeting the functional requirements. It also includes:

- Test all links are working correctly and there is no broken link.
- Test forms. For examples: does it shows some error if user skips mandatory fields, does default values are being populated, does the data in the form submitted to the database? Also, test all create, insert, update and delete operations.
- Test cookies. For example: do cookies are deleted when the cache is cleaned and does your site ask for credentials when cookies are deleted?
- Validate HTML, CSS standards.
- Test negative scenarios to check if correct error messages are shown.


**Browser Testing:**
Browser Testing includes:
- Browser Compatibility: Testing website on each and every browser.
- Operating Environment Compatibility: Test website on Windows, Mac, UNIX, and Linux.
- Mobile Device Compatibility: Test website on different mobile devices, tablets.


**Usability Testing:**
The website should be easy to use. Usability Testing includes:
- Test the site Navigation: Menus, buttons, links should be visible to the user and should be consistent on all pages.
- Test the Content:
    - Check for the spelling error. 
    - Proper color and fonts should be used. 
    - The website should follow the UI standards. 
    - Search bar result should be accurate.
    - Content should be meaningful.
    - Images should have alt field.


**Interface Testing:**
Interface testing includes testing of the application server, web server and database server. Check if:
- All the interactions are executed correctly within these three servers.
- Correct messages are shown to the user if:
    - Errors are returned from the web server/database server.
    - The transaction is interrupted by the user.
    - The connection is lost.


**Database Testing:**
The database is the critical component of every website. It includes:
- Check if data is returned correctly from the database.
- Check if errors are handled properly and the message is shown to the user if the record does not exist in the database.
- Integrity should be maintained in the database.
- Check the response time of the query.


**Performance Testing:**
Performance testing means to check how many resources are needed by the application in order to complete the task. It includes:
- _Load Testing:_ If many users are accessing the same page/database, how the application does behave. 
- _Stress Testing:_ Determine the breakpoint of your application during peak load and check if your application crashes during peak load. How does it recover from the crash? 


**Security Testing:**
Security testing means checking if the confidential data stays confidential or not. It is very important to do security testing if you are building an e-commerce website where the user enters credit/debit card details. It includes:
- Unauthorized access should not be permitted.
- The application should not send important information in the query string.
- Any HTML or script should not be accepted by the application.
- Input validation checks should be applied.
- The session should be automatically killed after long user inactivity.
- If SSL certificate security measures are used, the user will be automatically redirected from HTTP page to https page.


**Crowd Testing:**
Crowd testing is in trend. In crowd testing, you select a large group of people (external to the organization) to execute some test cases which will not be executed by internal people. This is similar to beta testing. By doing this, you will be able to identify some critical defects that may be reported by your future customers.


In order to be a good Web Developer, you need to know each and every aspect of Website Development. So this blog is not important only for Tester but it’s equally important for a Web Developer.


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
