# billionaires-project

To recreate the environment, open billionaires-project.Rproj and run the following command in the (R) Console:
``` 
renv::restore()
```

## Contribute

Please, note that due to the time constraints, we do not have to be strict on these guidelines. However, if we can follow them, it would be great for our collaborations.

All code development must happen in branches. You should **never** push to main directly. The following branch naming conventions are to be followed for this project:

feature/<name> is for adding or removing a feature like plot or data source, e.g., feature/knn-classification
bugfix/<name> is for fixing a bug that makes the code not to work as expected, e.g., bugfix/broken-file-paths.
refactor/<name> is for refactoring code that does not affect the outputs, features or bugs, e.g., refactor/linear-regression.

Notes

Always use lowercase letters for branch names.
Push your changes to the remote regularly.
Branches should be short-lived. Once the work on a branch is completed, create a pull request to merge it into main.
Always request a reviewer when maling a pull requests.
Commit messages should follow Conventional commits specification.
