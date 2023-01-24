# DA-210/CS-181 Homework 1.e

The goal of this HW is to help you practice using Python functions as objects (including lambda functions) and list comprehensions.

**Note that you may complete this homework with one partner.  You must type up all of the code yourself, but you can work together and look at each other's code.  You _must_ include the name of your partner, if any, in the cell at the end of listcomp.ipynb.**

---

## Step 1: Functions as objects

Complete [`functions.ipynb`](functions.ipynb).  This notebook contains exercises related to using functions as objects (e.g., as parameters to other function calls), including when those functions are lambda functions.

---

## Step 2: List comprehensions

Next, complete [`listcomp.ipynb`](listcomp.ipynb).  This notebook contains exercises involving list comprehensions.

---

## Step 3: Submission

Recall the general  submission workflow, summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_1.e/functions.ipynb

    $ git add hw/HW_1.e/listcomp.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 1.e."
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```