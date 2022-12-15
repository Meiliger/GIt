# Git Practice

1. `$ pwd` - where am I now (path)
2. `$ ls`- show files in current directory
3. `$ cd git_tutorial/repos/githubrepo`- move to working catalogue
4. `$ git init` - start a new repository 
5. `$ mkdir gitfolder1`- create a new folder
6. `$ mkdir qa1 qa2 qa3`- create 3 folders
7. `$ cd gitfolder1`
8. `$ touch fileA.txt fileB.txt fileC.txt fileD.json fileE.json` - create 5 files (3 txt, 2 json)
9. `$ echo "some text" >> new_file.txt`- another way to create a new file
10. `$ notepad fileA.txt` - open the file with notepad.
11. Type "featureA", save it and close the notepad.
12. `$ cat fileA.txt` - inspect file content
13. `$ echo "featureB" > fileA.txt` - add a new entry to the "fileA.txt" file (on the first line)
14. `$ echo "featureC" >> fileA.txt` - add a new entry to the "fileA.txt" file (on the second line)
15. `$ git blame fileA.txt | grep featureC`- who made the change related to adding the "featureC" line
16. `$ vim fileA.txt` [ESC] :wq - edit the contents of the file “fileA.tx” with vim
17. `$ cd ..`
18. `$ mv gitfolder1/{fileB.txt,fileC.txt} qa1` - move 2 files to another folder
19. `$ cp gitfolder1/{fileD.json,fileE.json} qa2` - copy 2 files to another folder
20. `$ find -name fileA.txt` - search for a file by name (output - "./gitfolder1/fileA.txt")
21. `$ cd gitfolder1`
22. `$ head -n 2 fileA.txt`- output the first 2 lines from a text file
23. `$ tail -n 2 fileA.txt`- output the last 2 lines from a text file
24. `$ nano fileA.txt` - edit the contents of the file “fileA.tx” with nano
25. `$ grep 'featureB' fileA.txt`- view content in real time
26. `$ cd ..`
27. `$ git status`
28. `$ git add qa2` - add a file to the staging area
30. `$ git log` - used to view the commit history
31. `$ git commit -m "add qa2"` - new commit
33. `$ git remote add origin *link*` - created a link to the remote repository origin using the URL of this repository.
34. `$ git push -f origin master` - push changes from local repository to remote
35. `$ git branch featureX`- create the branch
36. `$ git branch`- view the list of branches in the local repository
37. `$ git branch -m featureX featureY` - branch renaming
38. `$ git checkout featureY` - switch to branch
39. `$ git checkout -` - switch to master
40. `$ git branch -d featureY` - delete the branch
41. `$ git checkout -b featureN` - create and switch to branch
42. `$ echo "simpletext" > fileR.txt`
43. `$ git add .`
44. `$ git commit -m "add fileR.txt"`
45. `$ git checkout -`
46. `$ git merge featureN` - merge commit
47. `$ git branch -d featureN` - delete the branch
48. `$ git commit --amend` - update previous commit
49. `$ git revert *hash*` - reverting the commit
50. ``
51. ``
52. ``
53. ``
54. ``
55. Создать файл “new.json” `$ touch new.json`
56. 
