# StatTheoryLabs
learnr tutorials and labs for a mathematical statistics course

### To install this package:

1. One time only (may need to reinstall for updates throughout the semester):

`remove.packages("learnr") ## might not need this if you do not have learnr pre-installed`

`remotes::install_github("rstudio/learnr")`

`remotes::install_github("rstudio-education/gradethis")`

`remotes::install_github("sastoudt/StatTheoryLabs")`


2. Thanks to Marney for this one: after install is complete (I know this seems weird, but go with it):

```remove.packages("htmltools")```

```install.packages("htmltools")```

Exit RStudio and then open it again.

#### Troubleshooting

- These packages have more recent versions available. Which would you like to update? --> If the list only includes `htmltools` say No.

- Do you want to install from sources the package which needs compilation? (in reference to `dplyr 1.0.3` instead of `dplyr 1.0.4`) --> No 

### Launch a lesson:

1. In the console (bottom left) type: `learnr::run_tutorial("lesson1", "StatTheoryLabs")`

### Stop a lesson 

1. Click stop sign on the left.

![](stop-tutorial.png)

#### Troubleshooting

- If you get some kind of error having to do with "parse" when you try to run a tutorial:
![](restartR.png) 

Click "Session" --> "Restart R" and try to run the tutorial again. 

![](restartR2.png) 

- The tutorial will often pop up in a new browser tab automatically. If you have a popup blocker, you might need to turn it off or update the settings.

![](popups.png) 

## Available Tutorials

- "first-day": first day activity to guess the color
- "hw2": check a homework problem empirically
- "hw3": check a homework problem empirically
- "hw4": check a homework problem empirically
- "lab0": Using Simulations to Check Theory
- "old_lab1": Estimation
- "capture_recapture": replacing "old_lab1" as "lab 1" (still workshopping)
- "lab2": Sampling Distributions and the CLT
- "project_prep": Introduction to Simulation Studies of Slope Estimation in OLS (still workshopping)



More coming soon... (in development Summer 2021)

## Lab Instructions

TBA


## How to Submit Google Form portion of Lab

Note: your Google form might look a little different, but the instructions stay the same.

![](submit-tutorial.png)

#### Troubleshooting

I can't see the Google Form at the end. 

Open in the browser (this should happen automatically if you use `run_tutorial` ), use Google Chrome, and make sure you are logged in to your Bucknell e-mail in the same browser (only Bucknell authenticated accounts can access the form to avoid any spam).

**Run into any problems not listed above? Let me know and when we figure it out we'll add to the list.**

