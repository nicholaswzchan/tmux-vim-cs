## FIND - Command line

*find* command syntax :

find *flags* *pathname* *expression*

To match files that end with .html:
>e.g. find . -name "\*.html" -print

```
Option          Description
-cmin time      True if the file has been modified within the last time minutes
-ctime time     Same as -cmin, but for units of hours, not minutes
-group name     True if the file owned by group name/ID
-iname pattern  Identical to -name except tests are case-sensitive
-iregx regx     Identical to -regex, but the regular expression is evaluated as case sensitive
-ls             Produces ls -l output for matching filters
-name pattern   True if the filename matches the specified pattern
-newer file     True if the file is newer than the specified reference file
-nouser         True if the file belongs to an unknown user (that is, a user ID that doesn't appear in either /etc/passed or NetInfo)
-perm mode      True if the file matches the specified permission.
-print          Prints the full pathname of the current file
-print()        Special version of -print that compensates for space and other non standard characters in filenames
-regex regex    Same as -name, but allow regular expression rather than just simple filename pattern matches
-size n         True if the file's size matches the specified size. Default unit is 512-byte blocks; append c for bytes, and prepend +"for more than" or - "for less than" tests
-type t         True if the file is of the specified type. Common types are d for directory, and f for regular files
-user name      True if the file is owned by specified user. name can be username or user ID number
-not            you can reverse the logix of any find test by prefacing it with the -not primary
-or             -or allow logical OR tests, rather than defult AND test between each primary
```

&& -prem
Option          Description
r               Read permission
w               Write permission
x               Execute permission
s               Special set-user-ID-on-execution or set-group-ID-on-execution permission

syntax=a(all),u(user),g(group), or o(other, that is, everyone who isn't the user or in the user's group)

```
e.g.  find /usr/bin -name "z*" -type f -prem +u=w -print
      find . -cmin +60 -type f -print |wc -l
      find . -not -name"\*.html" -type f -print  |grep -i warning
      find $HOME -name "html" -print() |xargs -o grep -i xyz.com
      find . -type f \(name -name "\*.txt" -or -name ".htm" \) -print
```
---------------

## mdls Command line
