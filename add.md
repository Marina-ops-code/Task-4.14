[< to Table of contents](./readme.md)


## git add

**git add** - Add file contents to the index.
This command updates the index using the current content found in the working tree, to prepare the content staged for the next commit. 

It typically adds the current content of existing paths as a whole, but with some options it can also be used to add content with only part of the changes made to the working tree files applied, or remove paths that do not exist in the working tree anymore.The ***git add*** command will not add ignored files by default. If any ignored files were explicitly specified on the command line, git add will fail with a list of ignored files.


```bash=
git add .
```