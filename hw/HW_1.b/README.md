# DA-210/CS-181 Homework 1.b

The goal of this HW is to help you review Python and explore Python's `os` module.

**Note that you may complete this homework with one partner.  You must type up all of the code yourself, but you can work together and look at each other's code.  You _must_ include the name of your partner, if any, in the cell at the end of filebasic.ipynb.**

---

## Step 1: Python review

Then, complete [`pythonbasic1.ipynb`](pythonbasic1.ipynb).  This notebook will help you continue to refresh your Python knowledge.  If you find that it's taking a long time or you're having trouble, let your instructor know and/or visit office hours.

---

## Step 2: OS Navigation in Python

Finally, complete the [filebasic](filebasic.ipynb) Jupyter notebook.  This notebook also asks you to give the time you spent on this homework.

---

## Step 3: Submission

You will submit your homework by using Git to *commit* your changes, and *pushing* them to Github.  Recall the general workflow, summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_1.b/pythonbasic1.ipynb
    
    $ git add hw/HW_1.b/filebasic.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 1.b."
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```