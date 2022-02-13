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

Rename a file (same for directories)

~~~bash
$ mv 'filename' 'newname'
~~~

<br>

Show elements on this directory

~~~bash
$ ls
~~~

~~~bash
$ ls 'path'
~~~

<br>

Show the structure of a directory

~~~bash
$ tree
~~~

~~~bash
$ tree 'path'
~~~

<br>

Create an empty file

~~~bash
$ touch 'filename'
~~~

<br>

Get a file absolute path

~~~bash
$ readlink -f 'filename'
~~~

<br>

Print absolute path of a file

~~~bash
$ readlink -f ../file/relative/path
~~~
