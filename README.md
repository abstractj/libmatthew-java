[![Build Status](https://travis-ci.org/abstractj/libmatthew-java.svg?branch=master)](https://travis-ci.org/abstractj/libmatthew-java)

# libmatthew-java

## Unix Sockets Library

This is a collection of classes and native code to allow you to read and write
Unix sockets in Java.

## Debug Library

This is a comprehensive logging and debugging solution.

## CGI Library

This is a collection of classes and native code to allow you to write CGI
applications in Java.

## I/O Library

This provides a few much needed extensions to the Java I/O subsystem. Firstly,
there is a class which will connect and InputStream with an OutputStream and
copy data between them.

Secondly there are two classes for inserting into an Input or OutputStream pipe
a command line command, so that everything is piped through that command.

Thirdly there are a pair of classes for splitting streams in two. This can
either be to two OuputStreams, or to an OutputStream and a file. Equivelent to
the UNIX tool tee in UNIX pipes.

## Hexdump

This class formats byte-arrays in hex and ascii for display.

## Credit

All the hard work in this project is credited to [Matthew Johnson](http://www.matthew.ath.cx/projects/java/).

## Acknowledgments

Thanks to [Diego López León](https://github.com/diega) for the initial work with Maven. This fork was pretty much based on the work done [here](https://github.com/diega/libmatthew-java).


