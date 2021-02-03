# GitFlow

## What is GitFlow?
GitFlow is a branching methodology when using version control. It determines the development branches that are set up and how they are utilized to make merging easier.

## Parallel Development
GitFlow allows for parallel development by isolating code changes into separate branches that have their own purpose. Each branch can be switched to easily by committing changes and switching to another branch. This isolates work and can allow for hotfixes, long term development, and releases that are not ready for the main production branch.

## Develop & Master Branches
Normal development is done using just one master branch to record the history of development. In GitFlow, the development is split off into Develop and Master branches. The Develop branch handles integration of features and has a more detailed history of commits whereas the Master branch is used to push final releases into production and has an abridged history.

[](https://wac-cdn.atlassian.com/dam/jcr:2bef0bef-22bc-4485-94b9-a9422f70f11c/02%20(2).svg?cdnVersion=1438)

