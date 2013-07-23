git-revision-exporter
=====================

Given a certain sha generate a change log of all the modified files and export them from a local working directory into another folder for easy deployment to a live server environment

The initial idea is to have some based of this command where you can generate a list of changed files given a git sha.

```
git diff-tree -r --no-commit-id --name-only --diff-filter=ACMRT $commit_id
```


###RoadMap

##Stage 1:
Working version of exporter that is able to take a list of changed files and export them into 

##Stage 2:
Updated interface of exporter that allows you possibly select from a list of all the commits (this might not even be possible).

##Stage 3:
Javascript version of exporter using node.js to make it more platform independant.