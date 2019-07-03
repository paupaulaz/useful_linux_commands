# Useful Linux commands

## This file contains some useful commands gathered from various places.
_____________________________________________

### Terminal commands:

* going back to the last working directory:

```shell
cd -
```

* fix the (long) previous command in a text editor:
```shell
fc
```

* print out the last used commands:
```shell
history
```

* add a command to history without executing it:
```shell
history -s <command>
```


* execute the last command as root:
```shell
sudo !!
```


### Keyboard shortcuts:

* activate reverse history search:
```
ctrl + maj + r
```

### Other Terminal tricks:
* difference between piping and redirecting:

# piping is for sending the output of a command to the input of an other. For ex:
```shell
ls | head -3
```

# redirecting is for writing the output to a file (existant or not):
```
cat file.txt > file_copy.txt
```

# if the file already exists, use '>>' to append to the end.
