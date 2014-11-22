CppProjectStarter
=================

Bash script that accepts a list of class names (classes.txt) and generates useful boilerplates of all .cc and .h files you'll need.

All .cc files #include their corresponding .h files, use namespace std, and provide a default Classname::(){} namespace resolution operator header.

All .h files have properly named include gurads.

Use by creating classes.txt as a whitespace-separated list of Classnames and running this bash script in the same directory.

Sample Usage:
=================
classes.txt:
```
Tree
```

$./generate

Produces the following:

tree.h:
```c
#ifndef __TREE__H__
#define __TREE__H__

class Tree : public XXX {

  public:

}

#endif
```

tree.cc:
```c
#include "tree.h"
using namespace std;
Tree::(){

}
```

