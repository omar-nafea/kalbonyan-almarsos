# Git-Essential-Training
Git is software that keeps track of changes that you make to files and directories.
Git is referred to as a version control system or VCS 
also version control. Because of this they're also called source code management tools or SCM 
## the history 
### source code control system sccs
closed source, free with linux stored original version and sets of changes
### revision control system rcs
open source, stored latest version and sets of changes
### concurrent version system cvs
open source, multiple files for entire project, multi user repositories
Without saving previous versions of the file separately, no changes are tracked.
### apache subversion svn
open source, track text and images, track file changes collectively
### bitkeeper scm 
closed source, proprietary, distributed version control, community version was free, used for source code of linux kernal
### git born when the community stop being free
created by linux torvalds, replacement for bitkeeper to manage linux kernel source code, distributed version control, open source and free software
compatible with linux macos windows, faster than scm
### Git is distributed version control. 
- Different users each maintain their own repositories instead of working from a central repository, and the changes are stored as sets or patches, focused on tracking changes, 
- not the versions of the documents. but, CVS and SVN track the changes that take to get from version to version of each different file, or the different states of a directory.
- Git really focuses on these change sets, and encapsulating a change set as a discrete unit, and then those change sets can be exchanged between repositories. 
- there's no single master repository. There's just many working copies, each with their own combination of change sets.
If you have just completed editing two files, what is the result of the following series of commands, executed without any other action? git add . git commit -m "Initial commit" git add . git commit -m "Another commit"
Git will stage both files and commit them with the message "Initial commit." The next set of add and commit messages will have no effect on the repository.
1. people 

```html
<html>
<head>
</head>
<body>
</body>
</html>
```
