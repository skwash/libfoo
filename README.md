# libfoo

g++ -c -fPIC foo.cpp -o foo.o
g++ -shared -Wl,-soname,libfoo.so -o libfoo.so  foo.o

http://stackoverflow.com/questions/145270/calling-c-c-from-python

