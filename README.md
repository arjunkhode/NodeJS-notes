# NodeJS-notes

- At the core of Node is the V8 JavaScript engine.
- v8 is written in C++
- it converts JS into machine code.

EcmaScript is a standard for JavaScript language.
It was created because in the old days, Netscape, Microsoft among other companies were trying to create different standards for JavaScript.
ECMA stands for European Computer Manufacturers Association.

We can add features to JS by using V8 hooks in C++
For example a simple .cc file could contain the following V8 library to add more functionality to V8. 
'''
  #include <include/v8.h>
```

Node JS is a C++ program embedded in V8 that adds a whole bunch of extra features to JS

