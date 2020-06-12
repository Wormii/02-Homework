# 02-Homework

https://jam-madrigal.github.io/02-Homework/

Refactoring code to make it more accessible. Including things like removing extraneous code, adding comments, simplifying elements and ids. Some broken functionality was also restored.

![image](https://user-images.githubusercontent.com/65047802/84466111-7aaec000-ac2d-11ea-89eb-3b64b0036421.png)
![image](https://user-images.githubusercontent.com/65047802/84466299-f1e45400-ac2d-11ea-86b8-21a6837ec1d2.png)

An example of some code cleaned up with semantic elements and a descriptive comment to make code easier to find and understand at a glance, and the portion of the deployed webpage to which it refers.

# Getting-started

- Began by adding comments to break up the different sections of the code and make it more readable for whoever would look at the code in the future. Each portion of the code is now broken up with comments that help it easier to isolate specific containers.
- Test links for functionality
- Verified every image had an alt or description
- Split up some convoluted parts of the code
- Started looking to clean up the div soup with alternative html tags
- Began consolidating .css classes

# Functional changes

- The title in line 7 was changed to clearly include the brand name.
- The search engine optimization link was found dysfunctional; fixed by making it consistent with the other two sections by adding a class of the same name as its id.
- Added alts for the 3 images in the sections that detail the company services.
- Described the background "hero" image
- Removed extraneous code from the .seo class in the .css file
- Cleaned up the header class into just being a header semantic element
- Cleaned up header div into a nav semantic element
- Cleaned up the div class content into a main semantic element
- Consolidated the several .benefit classes into catch-all .benefit, .benefit img, and .benefit h3 classes
- Renamed benefits class into an aside semantic element
- Consolidated several main content classes while retaining their unique ids to preserve navbar function
- Further consolidated latter main content classes into a section html semantic element
- Simplified footer class into a footer semantic element
- Added comments to the css to make it quicker to read at a glance
