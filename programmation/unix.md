# The Unix Shell
https://swcarpentry.github.io/shell-novice/01-intro.html



## Navigating, working, and creating files and directories

print working directory:
```sh
pwd
```

listing:
```sh
ls
```

creating directory:
```sh
mkdir [path]
```

creating a file:
```sh
nvim [file]
```

deleting a file:
```sh
rm [path]
```

moving and/or renaming a file:
```sh
mv [old] [new]
```

copying a file:
```sh
cp  [old] [new]
```

#### Using wildcards for accessing multiple files at once
\* -- a wildcard, which represents zero or more other characters. 
? -- is also a wildcard, but it represents exactly one character. 


## Pipes and Filters 

`wc [file]` is the ‘word count’ command: it counts the number of lines, words, and characters in files (returning the values in that order from left to right). 

