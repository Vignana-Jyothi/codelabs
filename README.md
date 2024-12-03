# codelabs

This repository is for students to practice github using codelabs. 

## Practice.
View the complete instructions at [Community codelabs page](https://community.vnrzone.site/e/en/StartupZone/codelab/Github)


### File Creation
Createa a new file in users. The file name can be your roll_number.text

Example:
touch users/99071a0508.txt

cat >> users/99071a0508.txt

[Control+D]

### Create Git envelop

git status
> (base) kp@kuru:~/codelabs$ git status
> On branch main
> Your branch is up to date with 'origin/main'.
> 
> Changes not staged for commit:
>   (use "git add <file>..." to update what will be committed)
>   (use "git restore <file>..." to discard changes in working directory)
>    modified:   README.md
> 
> no changes added to commit (use "git add" and/or "git commit -a")

```
git add users/99071a0508.txt
git status
```
> (base) kp@kuru:~/codelabs$ git status
> On branch main
> Your branch is up to date with 'origin/main'.
> 
> Changes to be committed:
>   (use "git restore --staged <file>..." to unstage)
>   modified:   README.md

```
git commit -a -m "Krishna Prasad user file"
```
> [main 778905c] Krishna Prasad README changes
> 1 file changed, 27 insertions(+), 12 deletions(-)

```
git status
```
> On branch main
> Your branch is ahead of 'origin/main' by 1 commit.
>   (use "git push" to publish your local commits)
> 
> nothing to commit, working tree clean

```
git push
```