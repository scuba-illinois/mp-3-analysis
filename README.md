# MP-3: The Causal Effect of Positive Feedback

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
* Visually examine pre- and post- treatment data for trends

## Setup

Download the dataset from [here](??). The dataset consists of all posts from r/aww that were submitted in year 2022. 

## Your Task

You will go through the provided Jupyter notebook, [MP-3.ipynb](./MP-3.ipynb), and fill in all the marked checkpoints. The lab is very structured and provides a lot of code for you, so all you need to do is read along, run the provided code, and fill in requested code cells.

We have provided you with some test cases. **Make sure you pass these before moving on!** They're designed to help make sure you're on the right track.

## What to submit

* *Your python code* (`MP-3.ipynb`): upload your completed notebook with all checkpoints filled out and all code outputs visible.
* *A written report*:

## Grading

You will be evaluated on the tasks as follows:
