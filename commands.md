## Index
- [Most common ones](#most-common-ones)
- [Some advanced](#some-advanced)

### Most common ones 

<br>

Remove a file

~~~bash
$ rm 'filename'
~~~

~~~bash
$ $ rm ./path/to/the/file
~~~

<br>

Remove a directory
~~~bash
$ rm -d 'dirname'
~~~

~~~bash
$ rmdir 'dirname'
~~~
<br>

Move a file
~~~bash
$ mv 'filename_or_directory' /destination/root
~~~

<br>

Get a file absolute path
~~~bash
$ readlink -f 'filename'
~~~

~~~bash
$ readlink -f ../file/relative/path
~~~

<br>

Rename a file (same for directories)

~~~bash
$ mv 'filename' 'newname'
~~~

<br>

Print something (a variable, string...)

~~~bash
$ echo $variable
~~~

~~~bash
$ $ echo 'String'
~~~

<br>

Show elements on this directory

```bash
$ ls
```

Create files
~~~bash
$ touch 'filename'
~~~


### Some advanced

Install something

~~~bash
$ sudo snap install 'program' --setting
~~~
