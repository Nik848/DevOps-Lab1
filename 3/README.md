# Experiment 3: Record Commands, Pipeline Configurations, Screenshots, Commit History and Observations

## Aim

To maintain a record of the commands, Jenkins pipeline configurations, screenshots, commit history, and observations from the completed experiments.

## 1. Commands Used

The following commands were used during the experiments:

* Created experiment folders inside the Git repository.
* Created and edited Jenkinsfiles using Visual Studio Code.
* Checked Docker and Jenkins status.
* Added files to Git.
* Committed changes to the repository.
* Pushed changes to GitHub.
* Created and executed Jenkins Pipeline jobs.
* Checked Jenkins console output to verify execution.

## 2. Pipeline Configurations

### Experiment 1

A Jenkins Declarative Pipeline was configured with the following stages:

* Build
* Test
* Deploy

The pipeline was connected to the GitHub repository and configured to use the Jenkinsfile located in the `1` folder.

### Experiment 2

A Jenkins deployment pipeline was configured with:

* SCM build trigger
* Build stage
* Deployment stage
* Post-build action

The Jenkinsfile was located in the `2` folder.

## 3. Screenshots

### Experiment 1

**Paste the screenshots from Experiment 1 here.**

* Jenkinsfile configuration
* Pipeline execution
* Console output

### Experiment 2

**Paste the screenshots from Experiment 2 here.**

* Build trigger configuration
* Automatic pipeline execution
* Deployment and post-build execution

## 4. Commit History

**Paste Screenshot 1 here**

*Figure 1: Git commit history showing the commits made for the experiments.*

The commit history was maintained to track changes made to the Jenkinsfiles and application files throughout the experiments.

## 5. Observations

1. Jenkins successfully executed the declarative pipeline stages.
2. Jenkins was able to retrieve the pipeline configuration from the GitHub repository.
3. SCM polling was used to detect repository changes.
4. Changes pushed to the repository could trigger a Jenkins pipeline automatically.
5. Jenkins console output was useful for verifying the execution status of each stage.
6. Git commit history provided a record of changes made during the experiments.

## Result

The commands, Jenkins configurations, screenshots, commit history, and observations were documented successfully for the completed experiments.
