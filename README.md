# MP-3: Data Analysis

This repository contains the instructions and template files to complete our third mini-project!

## Overview

There is significant research on online governance through punitive moderation actions (e.g., content removal, user bans, quarantines, etc.). However, these methods lack the ability to teach users how they *should* behave and have no capacity to inform bystanders of positive norms. One way to proactively teach community norms is by providing positive feedback to high quality contributions.
In this MP, we will explore the impact of receiving positive feedback on user behavior. 

In this assignment, we will leverage  Reddit *score*, a contribution's aggregated upvotes and downvotes, to look at online moderation from a positive angle: *how can positive feedback impact user behavior*? The RQs and data for this lab is drawn from [Lambert et al. 2025](https://drive.google.com/drive/u/1/folders/1d0nN6vdrDaSAFNYFGxiQHnai2LYTVkmy).

> **RQ 1: How does receiving high score on a post affect an author's posting frequency?**
>
> **RQ 2: How does receiving high score on a post affect an author's future score?**

To answer these questions, we'll work closely with the treatment and control data to do Propensity Score Matching (PSM)! Matching helps us build a strong control group to compare against our treatment group, allowing us to more confidently attribute observed effects to the treatment itself.

## Learning Objectives

By the end of this MP, you will be able to:
* Use Propensity Score Matching (PSM) to match treatment and control data
* Measure and interpret match quality with Standardized Mean Difference (SMD)
* Perform a Wilcoxon Signed-Rank test
* Run and interpret Difference-in-Differences (DiD) regression

## Setup

Download the dataset from [here](https://drive.google.com/file/d/1HBCftCDTAglt5HVectVMOU3bLCcqk8HM/view?usp=drive_link). The dataset consists of all posts from r/aww that were submitted in year 2022. 

## Your Task

You will go through the provided Jupyter notebook, [MP-3.ipynb](./MP-3.ipynb), and fill in all the marked checkpoints.
The MP is very structured and provides a lot of code for you, so all you need to do is read along, run the provided code, and fill in requested cells  (both code and markdown). 
**You must run every provided cell for the assignment to work properly.**

We have provided you with some test cases. **Make sure you pass these before moving on!** They're designed to help make sure you're on the right track.

Some of the checkpoints also have written components and we have provided markdown cells for you to fill in your answer.

## What to submit
* *Your python code* (`MP-3.ipynb`): upload your completed notebook with all checkpoints filled out and all code outputs visible to Canvas.

## Grading

You will be evaluated on your answers for each of the 7 checkpoints. Point values are noted alongside each checkpoint in the notebook.
