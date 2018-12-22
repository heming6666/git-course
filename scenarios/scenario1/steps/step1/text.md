It's important to note that you will always be *inside* a single directory when using the terminal. The default behaviour is that when you open a new terminal you start in your own *home* directory (containing files and directories that only you can modify). To see what files and directories are in our home directory, we need to use the [ls][] command. This command lists the contents of a directory.

If we run the `ls`{{execute}} command we should see something like:

```bash
learner@host01:~$ ls
a_directory another_directory
learner@host01:~$
```

There are three things that you should note here:

1. The `learner@host01:~$` text that you see is the Unix [command prompt][]. In this case, it contains a user name ('learner'), the name of the host computer (host01), and the name of the current directory ('~', more on that later). Note that the command prompt might not look the same on different Unix systems. In this case, the `$` sign marks the end of the prompt.
2. The output of the `ls` command lists two things. In this case, they are both directories, but they could also be files. We'll learn how to tell them apart later on.
3. After the `ls` command finishes it produces a new command prompt, ready for you to type your next command.

The `ls` command is used to list the contents of _any_ directory, not necessarily the one that you are currently in. Try the following:

`ls /`{{execute}}

```bash
learner@host01:~$ ls /
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
```

`ls /etc/perl`{{execute}}

```bash
learner@host01:~$ ls /etc/perl
CPAN  Net
```

[ls]: http://en.wikipedia.org/wiki/Ls
[command prompt]: http://en.wikipedia.org/wiki/Command_line_interface
