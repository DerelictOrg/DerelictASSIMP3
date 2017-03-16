DerelictASSIMP3
===============

A dynamic binding to [Assimp3][1] version 3.3 for the D Programming Language.

Please see the sections on [Compiling and Linking][2] and [The Derelict Loader][3], in the Derelict documentation, for information on how to build DerelictASSIMP3 and load ASSIMP at run time. In the meantime, here's some sample code.

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
[2]: http://derelictorg.github.io/building/overview/
[3]: http://derelictorg.github.io/loading/loader/