Do you remember the DevOps Cycle and Stages of DevOps? If not visit the Week1 file and come back.

# Version Control System VCS
- Software tool used to manage changes to code.
- It allows developers to track and manage changes to files, collaborate and maintain a record of revisions and updates.

## Types of VCS
- **Centralized:**   
   * A central repository serves as the authoritative source for all changes.      
   * Developers check out files from the central repository, make changes, and then check them back in(push). 
   * Shouldn't have a working directory
   * Example: Subversion (SVN)

- **Distributed:** 
   * It creates a local repository on each developer's machine. 
   * Allows developers to work offline and synchronize changes with each other as needed.
   * Example: Git, Mercurial
 
# Git
Git is a popular version control system used in Agile development.

# Git Workflow

![image-1536x861](https://user-images.githubusercontent.com/128154979/228325119-c82ebb8d-1b69-4332-81de-f9544b8c631c.png)

It has four core elements:
* Working directory
  * Staged: updated file is ready to be committed to LR
  * Modified: Updated file not yet stored in LR
  * Commited: Updated file committed and stored in LR
* Staging Area
* Local Repository
* Remote/ Central Repository

**Push/ Pull:** 
   
   You make changes in your local repository privately on your PC and push them to the Remote repository for everyone to see.
   
   Others can pull your changes from the RR to their LR and integrate changes to their workspace and vice versa.

# Git Repository Guidelines

1. **Branching:** 
   * Branches are _pointers to commits_
   * Work on new feature without affecting main codebase
   * Create local branch, make changes in it/ experiment and then merge it to the main branch
   

2. **Committing Code:**
   Commit small changes focused on a single feature or change, and commit frequently to keep a history of changes.

3. **Code Review:** 
   Review code before merging it into the main branch to ensure it meets coding standards and doesn't introduce bugs.

4. **Continuous Integration and Deployment:** 
   Teams should automate testing and deployment processes to ensure that changes are tested and deployed quickly. 

5. **Versioning:** 
   Teams should use versioning to keep track of changes and releases. This includes creating tags( _tag is like a branch only that it doesnt changes when a new commit is made_ ) for each release and ensuring that version numbers are consistent across all components of the system.

By following these guidelines, teams can ensure that their Git repository is well-maintained and supports the Agile development process.

