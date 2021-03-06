# libMeshb version 7.12
A library to handle the *.meshb file format.

# Overview
The Gamma Mesh Format (GMF) and the associated library libMeshb provide programers of simulation and meshing software with an easy way to store their meshes and physical solutions.

The GMF features more than 80 kinds of data types, like vertex, polyhedron, normal vector or vector solution field.

The libMeshb provides a convenient way to move data between those files, via keyword tags, and the user's own structures.

Transparent handling of ASCII & binary files.

Transparent handling of little & big endian files.

Ultra fast asynchronous low level transfers.

Can call user's own pre and post processing routines in a separate thread while accessing a file.

# Build and use
The libMeshb library is written in ANSI C.

It is made of a single C file and a header file to be compiled and linked alongside the calling program.

It may be used in C, C++, F77 and F90 programs (Fortran 77 and 90 APIs are provided).

Tested on Linux, Mac OS X, and Windows 7.
