# Simple Shell Project In C

### Table of Contents

 [How To Use](#how-to-use)


---

#### Technologies

- C


## **How To Use**


### *In order to initialize the program, please run the code below
[Back To The Top](#simple-shell-project-in-c) on a Unix Shell environment.*
```html
    ./hsh
```
### *Here is the list of supported built-in commands*
```html
    Commands that are found at the <b>/bin/<b> path.
    exit - Exits the shell.
    env - Prints the current environment.
    setenv - Initializes a new environment or modifies an existing one.
    unsetenv - Removes an environment variable.
    cd - Changes current directory of the process.
    alias - Prints a list of all alliases
    help - Prints the help documentation.
    history - Prints list of executed command history
```
### *Special conditions handled include the following:-*
```html
    - Ctrl+C will not exit the shell, instead it is treated as Enter.
    - ; command separator.
    - || and && command-line logical operators.
    - $? and $$ variables.
```
