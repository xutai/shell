learn and take note



```
first of all, this is shell command!
markdown

echo:

> means write to
>> means append to

ref: How to append multiple lines to a file
,
Using echo; What is difference between > and >>


-------------------
write in single line
-------------------


echo "{content}" >> {filename}
echo "# yoshi" >> README.md
'#' markdown langauge, will create level 1 heading. then append the content to README.md file

-------------------
write in multiple line:

the last line must end with ' or ",
if ignoring '>>', then it will not create files,
but end the command

echo "
....
....
" >> README.md
-------------------
-------------------
-------------------
        
```

ex:

```
$ echo "
# shell
i will learning this one
> README.md
" > README.md

```

