# Git branching
The git branching model used was [Git Flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow). It defines a set of standard branches and workflows for managing development and releases. It is a popular choice for software development teams because it provides a clear and structured way to collaborate and maintain code quality. Some of the advantages of using Git Flow are:
- **Improved collaboration:** Git Flow promotes collaboration among team members by defining clear roles and responsibilities for each branch. 
- **Better code quality:** By separating development work into feature branches, Git Flow helps to ensure that code is thoroughly tested and reviewed before it is merged into the main branch. 
- **Easier releases:** Git Flow makes it easier to manage releases by providing a clear path from development to production. 
- **Reduced risk:** Git Flow helps to reduce the risk of introducing bugs into production by providing a way to isolate changes and test them thoroughly before merging them into the main branch.

# Commits methodology
As the repository used is common to both curricular units (ARSOFT and ODSOFT) and in order to allow an easy analysis of the work developed, the following commit methodology was adopted:

- First suffix
  - `[ARQSOFT]` --> Commit related to the ARSOFT project
  - `[ODSOFT]` --> Commit related to ODSOFT project
  - `[COMMON]` --> Commit related to both curricular units
<br></br>
- Second suffix
  - `Add:` --> Created something new in the repository
  - `Update:` --> Updated something that already existed
  - `Delete:` --> Deleted something that already existed