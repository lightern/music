# Some stuff for music hobby

### Commands for jriver
```
=fixcase([artist])
=fixcase([album])
=RemoveLeft([artist], 3)
=RemoveLeft([name], 3)
# Only first part of the name
=regex([Name],/#(.+)( -)#/, 1, 0)
# Only last part of the name
=regex([Name],/#(- )(.+)#/, 2, 0)
```
