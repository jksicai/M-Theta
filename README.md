# M-Theta
Git Feature Branch Workflow

In the branching model, you are required to create a Production branch which will act as the main (master) branch, an Integration branch which will again have two branches inside it namely Feature 1 and Feature 2, and a Hotfix branch which will be used for fixing any issues that could come up from Integration or Production branches.

Steps to perform:
1.	Start with the Production branch (master branch), and then create a HotFix and Integration branch
2.	Subsequently, create Feature 1 and 2 branches that integrate to the Integration branch as shown in the above figure
3.	Commit some changes in the Feature 2 branch and merge it into the Integration branch. Delete this branch once merging is complete
4.	Commit some changes in the Feature 1 branch and rebase it to the Integration branch
5.	Merge the Integration branch into Hotfix and Production branch to update these branches
6.	Commit some changes in Feature 1 branch, and then merge it into Integration, Hotfix, and Production branch. Delete this branch once merging is complete
7.	Commit some changes in the Hotfix branch and merge it into the Production as well as the Integration branch

