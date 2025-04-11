```
How to remove the branches locally ?
git branch -d branch_name such as test or dev

```
```
How to remove the branches remotely ?

git push origin :branch_name such as test or dev

```
```
what is Annotated tags vs Lightweight Tags ?

Annotated tags
Annotated tags are more informative than lightweight tags. When creating an annotated tag, Git stores a full object in the repository that contains the tagger name, email, and date, a tagging message, and a SHA-1 checksum of the commit being tagged. Annotated tags are essentially Git objects that are separate from the commit objects they reference, whereas lightweight tags are simply pointers to specific commits.

The additional information stored in an annotated tag makes them useful for documenting significant events in the project's history. The tagging message can provide context about why the tag was created and what it represents. Additionally, annotated tags can be signed and verified to ensure their authenticity. Signed tags provide assurance that the tag was created by an authorized person and that the commit being tagged has not been tampered with.

Example:

git tag -a v1.2 -m "my version 1.4"

Lightweight tags
Lightweight tags, on the other hand, are simply references to specific commits. They do not store any additional information beyond the tag name and the commit ID. Lightweight tags are useful for marking temporary or internal points in the repository history, such as to label a specific commit for testing or debugging purposes. Lightweight tags are created with the git tag command without the -a or -m options.

Example:

git tag v1.2

```
```
when to use Rebase ?
  git rebase is essentially not good to work on public branches. However,
  git rebase can also be done on the same branch. By periodically performing an interactive rebase on local branch, you can make sure each commit mentioned in git history is focused and meaningful. This lets you write your code without worrying about breaking it up into isolated commits — you can fix it up after the fact.
```
```
How to List tags ?

 i list tags by commit   git tag 
```
```
How to delete tag locally and remotely?

to delete local tags  i will used to  commit  ( git tag -d v1.7 ) such as 

to delete remote tags  i will used to  commit  ( git push origin --v1.7 ) such as 

```
``` 
Adding Image

![imagename](imageLink)
![Zamalk my love] (zamalk.png);

```
Adding Image
![Zamalkmylove](zamalk.png)