---
title: "Instructor Guidelines (Updated September 12, 2016)"
output: html_document
---

## Putting Materials Online
All of the materials should be put online the day before the class. There are two sets of materials that should be uploaded, and feel free to contact [Spencer]("mailto:spncrfx@gmail.com"") with any issues.

### Class Materials (minimum requirement)
1. Request access from [Spencer](mailto:spncrfx@gmail.com) to push to the repository.
1. Clone the rstats_fall2016 repository onto your local machine.
1. Checkout the gh-pages branch on your local machine, by opening up a terminal, navigating to the local repository, and running the following line:

     `$ git checkout gh-pages`
     
1. Place a `.zip` folder with your materials (preferably named "x_description", where x is your week number and a one word description) into the files folder.
1. Navigate to the `_posts` folder and find your week's `.md` file.
1. Edit the heading information so that it is correct.
    - for the `materials:` section, make sure your file path is correct for the zip file you put in the `files/` folder. For example if your `.zip` file was named `x_description.zip`, you should change the materials line to be `materials: files/x_description.zip`
1. Push your changes (the added `.zip` file and the edited post)
1. Check that the materials can be accessed on the front page by clicking the `Cheatsheets and Files` button

### Class Materials (helpful!)
1. Navigate to your `_post` file (See number 4 above)
1. Edit the markdown file to contain a quick introduction to what you will be teaching. See [the week 1 example](../_posts/2016-09-09-Intro to R.md) for inspiration.

------------------------------

## Helpful tips
We have compiled a list of helpful tips that we have found to be effective while teaching these seminars. 

1. Keep it simple. Many attendees have never used R before, and you should always assume people do not understand how functions work, how to format input, and hot to interpret function output.
  - These are usually
1. If you give an example workflow, make sure to motivate the example, and relate each step back to the overall goal of the example.
1. You might think you are doing really simple examples, but you aren't. Make sure that you fully explain each step. Simple examples, thoroughly explained, are better than comprehensive examples cursorly explained.
1. Never say "never use x"
    - it gives the impression of why should I even try if there is so much that I need to learn. When you are initially starting, any small steps towards computational things is important and should be fostered. The irony isn't lost on me that I just broke my own rule :).



