
1. determine which shell software you're using
``` BASH
user@host: ps $$
```
2. change your shell software ( bash, zsh, csh, ... )
``` BASH
user@host: bash
```
3. print the bash version
``` BASH
user@host: bash --version
```
4. print the directory location of bash 
``` BASH
user@host: which bash
```
5. print the current user name
``` BASH
user@host: whoami
```
6. print the current computer name
``` BASH
user@host: hostname
```
7. determine if a command or token is recognized by the shell
``` BASH
user@host: type [token]
```
8. read all tokens from stdin and prints them to stdout
``` BASH
user@host: echo
```

9. suppress the automatic new line with `echo` command
``` BASH
user@host: echo -n
```

10. print the current working directory
``` BASH
user@host: pwd
```

11. print the contents of the current directory
``` BASH
user@host: ls
```
12. print the contents of a relative path within the current directory
``` BASH
user@host: ls [relative path]
```

13. return to the parent directory
``` BASH
user@host: cd ..
```

14. return to the previous directory
``` BASH
user@host: cd -
```

15. return to current user's home screen
``` BASH
user@host: cd
```
or 

``` BASH
user@host: cd ~
```
