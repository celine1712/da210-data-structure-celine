# DA-210/CS-181 Homework 2.g

The goal of this SW Lab is to learn how to use the `pandas` module to perform `pivot` and `pivot_table` transformation operations on `pandas DataFrame` objects, and to continue practicung normalizing tables in `pandas` to make data tidy.

**Note that you may complete this homework with one partner.  You must type up all of the code yourself, but you can work together and look at each other's code.  You _must_ include the name of your partner, if any, in the cell at the end of normalize2.ipynb.**

---

## Step 1: `pivot` and `pivot_table` operations

Complete Parts A-C of [pivot.ipynb](pivot.ipynb) to get some practice with `pivot` and `pivot_table` operations on `pandas` data frames.

---

## Step 2: Normalizing data sets

Complete Parts D-E of [`normalize2.ipynb`](normalize2.ipynb).  This notebook contains exercises using tabular transformations to normalize datasets, resulting in tidy data stored as `pandas DataFrame`s.

---

## Step 2: Submission

Recall the general submission workflow, summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_2.g/pivot.ipynb

    $ git add hw/HW_2.g/normalize2.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 2.g."
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```