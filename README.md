DerelictASSIMP3
===============

A dynamic binding to [Assimp3][1] version 3.2 for the D Programming Language.

Please see the [Derelict documentation][2], for information on how to build DerelictASSIMP3 and load ASSIMP at run time. In the meantime, here's some sample code.

```D
import derelict.assimp3.assimp;

void main() {
    // Load the Assimp3 library.
    DerelictASSIMP3.load();

    // Now Assimp3 functions can be called.
    ...
}
```

[1]: http://assimp.sourceforge.net/
[2]: https://derelictorg.github.io/