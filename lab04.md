## CLI(command line interface) vs GUI (graphical user interface)
---
| CLI | GUI |
| --- | --- |
| Have to remember commands | Easy to use |
| keyboards, mostly | Mouse mostly + Some keyboard shorcuts |
| Relatively fast | Relatively slow |
| Scripts enable automation and record | Manual labors required for repetitive tasks |
| Basic enviroment for developer | For daily user |

## shell commands
---
| Command | explaination |
| --- | --- |
| pwd | shows the current path in a hierachical directory |
| cd | change directory ex) cd test1 |
| ls | list files and directories |
| cp | copy files and dirctories ex) cp file1 file2(if file2 does not exist, it is created) |
| mv | move files and directories or rename them ex) mv file1 file2 |
| rm | delete files and directories ex) rm file1 file2 |
| mkdir | make a new directory |
| exit | exit terminal |
| help | explain command |
| man | check manual of command |

### path arguments
/ : root

. : current directory

.. : upper-level directory

~ : home of current user

/directory name : absolute path

./directory name : relative path

../directory name : relative path


### ls options
-l : show ddeatiled information (long format)

-lh : same as above, but size in units

### Wildcards
| Pattern | Matches |
| --- | --- |
| * | All filename ex) cp *.txt text_files |
| g * | All filenames that begin with the character 'g' |
| b *.txt | All filenames that begin with the character 'b' and end .txt |
| Data??? | Any filename that begins with "Data" followed by exactly 3 more characters |

