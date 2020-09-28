![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Bash

## Introduction

We are going to practice with [`bash`](<https://en.wikipedia.org/wiki/Bash_(Unix_shell)>), a shell and command-line language!

## Setup

1. Download the folder to your machine and navigate to it folder.

2. Run the following command (_without the `$` sign_):

```shell
$ ls
```

and you should see:

```shell
exercises  inputs  lorem  lorem-copy  modules  outputs  README.md
```

3. Try to do the following exercises without changing the directory.

## Exercises

1. Print in console "Hello World".
2. Create a directory called `new_dir`.
3. Remove that directory.
4. Copy the file `sed.txt` from the `lorem` folder to `lorem-copy` folder.
5. Copy the other two files from the `lorem folder` to `lorem-copy` folder in just one line with the pipe `;`.
6. Show the `sed.txt` file content from the `lorem` folder.
7. Show the `at.txt` file and `lorem.txt` file contents from `lorem` folder.
8. Print the first 3 rows in `sed.txt` file from lorem-copy folder.
9. Print the last 3 rows in `sed.txt` file from lorem-copy folder.
10. Add `Homo homini lupus.` at the end of `sed.txt` file from `lorem-copy` folder.
11. Print the last 3 rows in `sed.txt` file from `lorem-copy` folder. You should see `Homo homini lupus.`.
12. Replace all `et` repetitions by `ET` in `at.txt` file from lorem folder to lorem-copy folder. Look the `sed` command.
13. Find who is the system user.
14. Find which is your actual path.
15. List all files with the extension `.txt` in lorem folder.
16. Count the rows in `sed.txt` file from lorem folder. Look concatenate `cat` and `wc` with the pipe `|`.
17. Count the **files** start with `lorem` in all directories.
18. Count how many times `et` appears in `at.txt` from `lorem` folder.
19. Count how many times `et` appears in `at.txt` from `lorem-copy` folder.

## Bonus

20. Store your `name` in a variable with `read` command.
21. Print that variable.
22. Create a new directory named with variable `name`.
23. Remove that directory.
24. For each file in `lorem` folder, print the number of characters of its name.
