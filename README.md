DerelictASSIMP3
===============

A dynamic binding to [Assimp3](http://assimp.sourceforge.net/) for the D Programming Language.

For information on how to build DerelictASSIMP3 and link it with your programs, please see the post [Building and Using Packages in DerelictOrg](http://dblog.aldacron.net/forum/index.php?topic=841.0) at the Derelict forums.

For information on how to load the Assimp3 library via DerelictASSIMP3, see the page [DerelictUtil for Users](https://github.com/DerelictOrg/DerelictUtil/wiki/DerelictUtil-for-Users) at the DerelictUtil Wiki. In the meantime, here's some sample code.

```D
import derelict.assimp3.assimp;

void main() {
    // Load the Assimp3 library.
    DerelictASSIMP3.load();

    // Now Assimp3 functions can be called.
    ...
}
```
