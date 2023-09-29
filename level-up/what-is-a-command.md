# Intro to the CLI - Level Up - What is a Command?

![Hero image](./assets/hero.png)

This question is harder to answer than you might initially hope, but in short, a command is anything you can execute directly from the command line.

Before going further, you should read [The Shell Level Up](./the-shell.md).

What makes this difficult to define is that there are four main types of commands you might use:

- **Built-in Commands:** These are commands directly integrated into the shell. For example, when you run `cd`, the shell handles these commands internally without invoking an external program.
- **Executable Programs:** Commands that correspond to external binaries or scripts on the system. The `ls` command is an example of this, along with any other application run from the terminal. When these apps are run, the shell spawns a new process to execute this external program.
- **Functions:** These are user-defined, callable mini-scripts, typically set in shell configuration files. Once a function is defined, it can be executed directly like any other command.
- **Aliases:** These are user-defined shortcuts for other commands. They're a way to reduce typing, standardize complex commands, or even correct common typos. When an alias is defined, it acts as a substitute for another command.