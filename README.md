# npm-resolution-bug

**Bug with symlink destination in npm < 7**

```
npm ERR! code ENOENT
npm ERR! syscall open
npm ERR! path ***/package.json
npm ERR! errno -2
npm ERR! enoent ENOENT: no such file or directory, open '***/package.json'
npm ERR! enoent This is related to npm not being able to find a file.
npm ERR! enoent 


```
