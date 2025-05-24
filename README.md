# 42 Campus

## Minishell 👑

Minishell is a project designed to give you hands-on experience in building a simplified shell that allows users to interact with the operating system through a command-line interface.   
This project was build in collaboration with [Luis Martín](https://github.com/luuismrtn).

### Features:
* Display a prompt when waiting for a new command.  
* Have a working history.  
* Search and launch the right executable(using relative path, absolute path or just the the name of the command)  
* Implement redirections: '<', '>', '<<', '>>'.  
* Implement pipes.  
* Handle environment variables.  
* Handle exit status with $?  
* Handle signals: 'ctrl-C', 'ctrl-\', 'ctrl-D'.  
* Implement builtins: 'cd', 'pwd', 'echo', 'exit', 'unset', 'export, 'env'.  

## How to use:

1. Clone the repository:
```c
git clone https://github.com/aldferna/MiniShell.git
```
2. Compile the project:
```c
make
```
3. Run the program:
```c
./minishell
```
4. Execute commands.
