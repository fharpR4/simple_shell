<h1> 0x16. C - Simple Shell</h1>
<p>This is a simple UNIX command interpreter<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg" alt="Shell"></p>

<h3>Compilation</h3>

<p>How Our Shell is compiled:</p>

<pre><code>gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh </code></pre>

<h3>Our Shell in modes:</h3>

<p>in interactive mode:</p>

<pre><code>$ ./hsh

($) /bin/ls
AUTHORS  built-ins.c  helper.c  hsh  man_simple_shell  path.c  README.md  shell.c  shell.h  str.c

($)

($) exit

$

</code></pre>

<p>But also in non-interactive mode:</p>

<pre><code>$ echo &quot;/bin/ls&quot; | ./hsh

AUTHORS  built-ins.c  helper.c  hsh  man_simple_shell  path.c  README.md  shell.c  shell.h  str.c

$

$ cat AUTHORS
# This file lists all individuals who contributed to the repository

Favour Lucky <favourluckyte314@gmail.com>

Temitope <temitope5555@gmail.com>
$
</code></pre>

<h4>List of helpful commands</h4>
<ul>
<li><code>cat</code> -  prints and concatenates files to the standard output</li>
<li><code>ls</code> - will list all files and directories in current working directory</li>
<li><code>cp</code> - copies a file into another file</li>
<li><code>grep</code> - helps to search for a file in a specific pattern</li>
<li><code>less</code> - will let you go backward and forward in the files</li>
<li><code>pwd</code> - given you the current working directory
<li><code>mv</code> -  helps to move one file into another file
</ul>

<h4>Exiting the Shell</h4>
<p><code>exit</code>To quit the shell the user can simple type in "exit"</p>

<h3>Authors: </h3>
<ul>
<li> Temi Tope </li>
<li> Favour Lucky </li>
</ul>
