<h1 align="center">Git</h1>

## Explanation:
- Git is a version control system essential for DevOps and Agile Development.
- Git can be said to be a component of Agile and DevOps development.
- Git works the same way an Agile or DevOps team should work.
- It can be used to track file changes among programmers.
- It supports non-linear workflows.

## States of Git:
 - **Modified files:** files that have been modified but not yet committed.
 - **Staged:** modified filed which is marked for inclusion in the next commit.
 - **Committed:** files that have been saved to the database.


## Branches of Git Workflow:
 - **Main Branches:**
    - Main:
      - typically referred to as "master".
      - contains code that is ready to be released.
      - created at the start of the project and maintained throughout the development.
      - other branches are merged into this one.
    - Develop:
      - contains pre-production features that are in the testing phase.
      - newly created features are in this branch.
 - **Supporting Branches:**
    - Feature:
      - the most common type of branch.
      - used when adding new features.
      - merged back into develop branch when the feature is completed and reviewed.
    - Release:
      - used when preparing new product releases.
      - includes features that need finishing touches or minor bugs.
    - Hotfix:
      - used to make quick changes in the main branch.
      - this branch is merged back into the main and develop branches.
  <p align="center">
  <img src="https://user-images.githubusercontent.com/73931604/229302451-25fbfb39-8b54-44b0-86c9-6a4674d83922.png">
  </p>
