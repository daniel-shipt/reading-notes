## Revisions and the Cloud

## What is Git?

* #### Git is a DVCS (Distributed Version Control System) that stores data in a file system made up of snapshots. Each time you save a changed version of your project (a commit), Git creates a snapshot of the file and stores a reference to it. If the file is unchanged, Git only stores a reference to the identical verson of it that is already stored.

* #### Every change applied to any file or directory is tracked by Git. As a result, Git will always detect file corruption or loss of information.

* #### Git is set up to minimize the possibility of damage to files, such as accidentally lost data. 

## Files in Git reside in 3 main states:
  * Committed
    * Data is safely stored in a local database.
  * Modified
    * Data has been updated but not committed.
  * Staged
    * Flagged a file's updated version to be committed in the next snapshot.

## Local Repository Structure

#### The Local Repository has 3 main components:
1. The working directory - Where all of the files reside.
2. The index - The area that is used for staging. 
3. The head - This points to the most recent commit.

## Some general Git commands 

``` git status - shows the state of your files ```

``` git add filename - allows you to track one single file ```

``` git add * - allows you to track all files in a repository ```

``` git commit -m “insert comment here” - after staging one or multiple files, you can comment on the changes you've made ```

``` git clone - allows you to clone a repository to a local directory (note: you have to add the url to the repo you are wanting to clone, after the word clone) ```

