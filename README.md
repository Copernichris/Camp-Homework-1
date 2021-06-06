# Descrption 

In this homework we were tasked with organizing code for an existing website. Work began in HTML where there was no semantic html to begin with. CSS follwed, where the main goal was to fix the out of order state and consolidate css as much as possible.

## HTML

 The following elements were added to the code to replace divs:

* Header
* nav
* figure
* main
* aside
* footer

Addition of these elements both increased readability and allowed for better consolidation of CSS. Functional changes to HTML included: 

* addition of alt tags to adhere to ADA rules
* addition of a title to the background image
* addition of an id tag to the search engine optimization section

Before the final change, the link would not function.

## CSS

Step one was to make sure CSS aligned with the order of the HTML. Comments were used to section off code by the corrresponding semantic element. Once code was in order, redundant CSS was consolidated by combining classes which all used the same CSS parameters. For things such as H1 or img tags, semantic elements allowed for single declarations. Elements which were previously refered to by the specific class they were in could now be better generalized with the semantic element. CSS was reduced by roughly 70 lines.

# Screenshot

![screenshot](https://github.com/Copernichris/Camp-Homework-1/blob/main/screenshot.PNG)

# Link
https://copernichris.github.io/Camp-Homework-1/