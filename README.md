CppProjectStarter
=================

Bash script that accepts a list of class names (classes.txt) and generates useful templates of all .cc and .h files you'll need.

All .cc files #include their corresponding .h files, use namespace std, and provide a default Classname::(){} namespace resolution operator header.

All .h files have properly named include gurads.

Use by creating classes.txt as a whitespace-separated list of Classnames and running this bash script in the same directory.

