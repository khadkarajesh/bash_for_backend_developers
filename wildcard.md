## Wildcard in linux
### *
Matches the zero or more characters

We have following list of files: 

1. file1.txt
2. file2.txt
3. file3.txt
6. file_bob.txt
7. file_alice.txt
8. file.txt

We want to get list of text files whose name starts with `file(anything i-e 1,2,3,_bob,_alice).txt`.

```bash
ls file*
```

```bash
# file1.txt
# file2.txt
# file3.txt
# file_bob.txt
# file_alice.txt
# file.txt
```

![Image](media/list_all_demonstration.png)

#### Excercise
1. List all text files which has `le` in file name?
2. List all files with extension `.sh`?
3. List all text file which starts with f as first character?
4. Delete files with extension .sh
5. Delete files with extension .txt


### ?
exactly one

### []

