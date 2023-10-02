# Intro to the CLI - Level Up - Flags

![Hero image](./assets/hero.png)

As demonstrated in [Navigating the File System](../navigating-the-file-system/README.md), we can use the `ls` command to see the files in a directory. 

The default behavior of this command is to not display hidden files (files that start with a `.`, like a `.gitignore-global` file). So how do we view files like this? We can add a what is called a *flag* to the `ls` command. Let's do this now!

```bash
ls -a
```

Here the letter `a` is a flag which is indicated by the `-`. Flags are extra modifiers you can optionally add to commands. They change the behavior of the command.

The `ls` command has quite a few other flags, such as `-l`. This flag lists the directories and files in a directory in a longer format with more details. Let's test it!

```bash
ls -l
```

We can even combine these 2 flags and run both simultaneously:

```bash
ls -a -l
```

Or use a cool shortcut by writing one dash `-` followed by the 2 options:

```bash
ls -al
```

We can write the flags in any order:

```bash
ls -la
```

Some applications also have long flags. These commands are spelled out words and are preceeded by 2 dashes `--`. A common long flag is `--help`, which some applications will have as a flag to display help information.
