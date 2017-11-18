Tiny Cookie Cutter Project
================

Hey, have you ever felt tired of looking for a file? But then it takes too much time to organize? Then let's "PLANET"

![planet](image/planet.jpg)

If you do things right from the beginning, it will be just a piece of cake to look for what you need. This tedious task should not be done manually, so let's me help you with my *tiny\_cookie\_cutter*.

### Getting to know cookie-cutter?

![Cookie Cutter](image/cookiecutter.PNG)

1.  What is a cookie-cutter?

Just an automated shell script that will help you to set up all the folders and needed files from the very beginning of your data science project.

1.  What does the script do?

-   It will ask you some questions about the projects.
-   Then create an organized directory for your next data science project.
-   The hierarchy template will look like this:

<!-- -->

         .
         |-- CITATION
         |-- README 
         |-- LICENSE
         |-- data
         |   -- # where you store your raw data file
         |   -- # metadata files - information about other data
         |-- doc 
         |   -- notebook.md         # electronic lab notebook recording your experiments
         |   -- manuscript.md       # text documents associated with the project 
         |-- results
         |   -- # where you store all result files
         |   -- # cleaned data file
         |   -- # analysis files
         |-- src
         |   -- # source code
         |-- bin
         |   -- # keep all the files you want to delete but not sure whether you will need it later
         

### How to use this cookie\_cutter?

**Step 1:** Clone this repository to your local repository or just simply download the `tiny_cookie_cutter` file.

-   If you don't know how to clone the repository, then download the zip file by clicking on the green button on the top right:

![download](image/download.PNG)

-   If you download the zip file, remember to unzip it and place the file where you want to operate.

**Step 2:** Save the `tiny_cookie_cutter` file in the folder **where you want to create your data science project**.

**Step 3:** Double click on the `tiny_cookie_cutter` file or run it by Git Bash/ Command

    **NOTICE**:  The script will ask you several questions about your project. Answer them and please notice:

-   Leave no blank space in your project name. One suggestion is to use underscore: *project\_name*
-   The author name can be your name or your company/ organization, depending on who will keep the copyright of this project. (Don't know about copyright? Check [this](https://simple.wikipedia.org/wiki/Copyright))
    -   The description can be long or short, up to you but you can always go back and update it later in the README.md file of your project.
    -   For LICENSE choice, please take a look at this [website](https://choosealicense.com/) for a clear explanation and choices. You can always change the LICENSE.md file later.

### The structure of this repository

-   `README`: Introduction and instruction to use the cookie\_cutter
-   `tiny_cookie_cutter`: An automated Shell script that would save you a lot of time.
-   `LICENSE`: License information of this product. (basically it's free for everybody to use)
-   `Image`: Storing image for this article

### Contributor

Who wrote this?

-   Not an alien, just a student named Duong Vu from University of British Columbia.

When it was created?

-   November 11, 2017

Any question?

-   Send it to my email: <dqvu.ubc@gmail.com>

### Source:

[Eduonix](https://www.eduonix.com) helps me with the interactive Shell Script part.

[Choose a License](https://choosealicense.com) gives information of license type and the contents of each type.

To end this, remember:

![lazy](image/organized-people.jpg)
