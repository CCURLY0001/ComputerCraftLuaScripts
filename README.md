# ComputerCraftLuaScripts
Repo for ComputerCraft (LUA) Scripts written by me



# You will probably have to run the following before being able to copy/paste to/from pastebin

In the computer's command line prompt, enter:
``` 
cp rom/programs/http/pastebin pastebin
edit pastebin
```

Goto line 24:

`
"http://pastebin.com/raw.php?i="..textutils.urlEncode( paste )
`

... and change it to:

`
"http://pastebin.com/raw/"..textutils.urlEncode( paste )
`

Save and exit, and the pastebin script should work on that system when executed from the root of the drive.
