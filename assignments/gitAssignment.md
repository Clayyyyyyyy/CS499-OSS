# Git Assignment

**INDIVIDUAL ASSIGNMENT**

**Value**: Part of in-class/short assignments grade

## Description

### Understanding the repo
1. Download [handson.zip](handson.zip) and unzip it. handson is a git repository. Using the commandline change the directory to "handson/"

2. Draw (or screenshot) the diagram of the commits and branches in repository.
    - Use `git branch` to list the branches in this repository.
    - Use `git checkout` to explore each branch.
    - Use `git log --decorate` to explore the structure of commits.

    ```



    ```

3. Now, try `git log --graph --all` to see the commit tree

4. Use `git diff BRANCH_NAME` to view the differences from a branch and the current branch.
   Summarize the difference from master to the other branch.

    ```




    ```

5. Write a command sequence to merge the non-master branch into `master`

    ```




    ```

6. Write a command (or sequence) to (i) create a new branch called `feature-bar` (from the `master`) and (ii) change to this branch

    ```
    
    
    
    ```
    
7. Edit B.java adding the following source code inside class B:
   ```
   public void bar(){
   
   } 
   ```

8. Write a command (or sequence) to commit your changes
   ```



   ```

9. Change back to the `master` branch and change B.java adding the following source code (commit your change to `master`):
   ```
   public static void main(){
      System.out.println("Hi")
   } 
   ```

10. Write a command sequence to merge the `feature-bar` branch into `master`. What happened?
   ```



   ```
   
11. Write a set of commands to abort the merge
   ```



   ```
   
12. Now repeat item 10, but proceed with the manual merge (Editing B.java). All implemented methods are needed. Explain your procedure
   ```



   ```


13. Write a command (or set of commands) to proceed with the merge and make `master` branch up-to-date
   ```



   ```



