# bento-icdc-static-content
This is repository that is only created to hold static content of ICDC Project. It will include branches for environments like DEV, QA, STAGE, PROD. 

 Environment | Linked Branch
| :---: | :---: 
ICDC-PROD  | production 🔒
ICDC-STAGE | stage 🔒
ICDC-QA | qa 🔒
ICDC-DEV | develop 🔒

> ❗ NOTE: Branches are protected. No direct commit can be made on any of thses branches.

Steps to contribute in this repository: 
1. Create a new and seperate branch based on "develop" branch, let's call it "xyz". (Don't forget to git pull the develop branch to keep it up to date before making a new branch)
2. Make changes on "xyz" branch, multiple commits are allowed. Commit those changes and push those commits to GitHub. 
3. Create a Pull Request (PR) from "XYZ" to "develop" branch. 
4. Get that Pull Request (PR) reviewed by at least one reviwer to get the PR Approved.
5. Reviewer needs to merge that PR into "develop" (Which is the base branch for this PR). 
6. Reviewer needs to delete "xyz" branch to keep the repository clean. 

>Here is the flow of how static content changes will flow from branch to branch: <br />
"XYZ Branch" -PR-> "develop" -PR-> "qa" -PR-> "stage" -PR-> "production"
