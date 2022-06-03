# bento-icdc-static-content
This is repository that is only created to hold static content of ICDC Project. It will include branches for environments like DEV, QA, STAGE, PROD. 

 Environment | Linked Branch
| :---: | :---: 
ICDC-PROD  | production 🔒
ICDC-STAGE | stage 🔒
ICDC-QA | qa 🔒
ICDC-DEV | develop 🔒

> ❗ NOTE: Branch are protected. No direct commit can be made on any of thses branches.

Steps to contribute in this repositry: 
1. Create seperate branch based on "develop" branch, let's call it "xyz". (Don't forget to pull develop to keep it upto date before making new branch)
2. Make changes on "xyz" branch, Multiple commits are allowed. Commit those changes and push those commit to github. 
3. Create Pull Request (PR) from "XYZ" to "develop" brach. 
4. Get that Pull Request (PR) reviewed by at least one reviwer to get PR Approved.
5. Reviwer needs to merge that PR into "develop" (Which is base branch for this PR). 
6. Reviewer needs to delete "xyz" branch to keep repositry clean. 

>Here is the flow how static content changes will flow from branch to branch: <br />
"XYZ Branch" -PR-> "develop" -PR-> "qa" -PR-> "stage" -PR-> "production"
