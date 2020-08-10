### Story - Task git braching model

1. When we merge task brach into story branch, with this selection 

![create-merge-commit](create-merge-commit.png)

We will come to the result commits are list down in the base PR (`feat/1`) like this 

![result-merge-commit](result-merge-commit.png)

Event though we have a `Verified` Badge, it still list all the commit from the merged PR

2. When we merge task branch into story branch, with this selection 

![create-squash-merge-commit](create-squash-merge-commit.png)

Then we will have only one additional commit message for the merge PR instead of list all commits

![result-squash-merge-commit](result-squash-merge-commit.png)