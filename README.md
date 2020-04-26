# gitlab-ci
this is git-lab-ci-cd exercise and content and cheat sheet.

# Jobs
* jobs are things that should be run in through git-lab pipeline. 
* when jobs doesn't have any stages they would be in test stage.
* Jobs of the next stage are run after the jobs from the previous stage complete successfully.
* when jobs are in the same stage they would be run in parallel.
* each job can have just one stage.
* after each job all thing would be remove unless you would define **artifacts**

# Stages
* when you wanna have jobs running in your order and you don't wanna run them as parallel.
* every stage can have multiple jobs as many as you want.
* you can have stages as many as you want.
* by default we are in test stage.
* before all stages we have .pre stage.
* after all we have .post stage.