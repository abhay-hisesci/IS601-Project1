# GitFlow

## What is GitFlow?
GitFlow is a branching methodology when using version control. It determines the development branches that are set up and how they are utilized to make merging easier.

## Parallel Development
GitFlow allows for parallel development by isolating code changes into separate branches that have their own purpose. Each branch can be switched to easily by committing changes and switching to another branch. This isolates work and can allow for hotfixes, long term development, and releases that are not ready for the main production branch.

## Develop & Master Branches
Normal development is done using just one master branch to record the history of development. In GitFlow, the development is split off into Develop and Master branches. The Develop branch handles integration of features and has a more detailed history of commits whereas the Master branch is used to push final releases into production and has an abridged history.

![](https://wac-cdn.atlassian.com/dam/jcr:2bef0bef-22bc-4485-94b9-a9422f70f11c/02%20(2).svg?cdnVersion=1438)

## Feature Branches
The Feature branches are used primarily to work on a new addition to the code base. There can be multiple Feature branches pertaining to different features being added to the project. The Feature branches are branched off of Develop rather than the Master branch. These branches are then merged back into Develop when changes are completed.

![](https://wac-cdn.atlassian.com/dam/jcr:b5259cce-6245-49f2-b89b-9871f9ee3fa4/03%20(2).svg?cdnVersion=1438)

## Release Branch
The Release branch is used to fork from a Develop branch when there are enough features added to the Develop branch for a release. The Release branch is then merged to the Master branch along with a version number to track releases. This strategy allows for multiple development teams to work on different releases concurrently.

![](https://wac-cdn.atlassian.com/dam/jcr:a9cea7b7-23c3-41a7-a4e0-affa053d9ea7/04%20(1).svg?cdnVersion=1438)
<img src="https://wac-cdn.atlassian.com/dam/jcr:a9cea7b7-23c3-41a7-a4e0-affa053d9ea7/04%20(1).svg?cdnVersion=1438" alt="release_branch_image" width="500"/>
