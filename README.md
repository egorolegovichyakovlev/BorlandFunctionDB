# Borland C++ Function ID database for Ghidra

These functions were gathered from **Borland Developer Studio 2006** "Dynamic Link Run Time Library" DLL files.

An extended version, which is built from all libraries contained in Borland Developer Studio directory:

`bds2006demangled.fidb` contains demangled function names of the whole Borland Developer Studio 2006 libraries directory.

And a lightweight version, which was generated only from the `cp3245mt.dll` file:

**`cp3245mt.dll`** *`914e1bc346e9ec6279f112509f5c3c38156f0bc2196fd1665dd0ee96e4b279ec`* (sha256sum)

`cp3245mt_mangled.fidb` contains mangled function names (unprocessed, not readable).

`cp3245mt_demangled.fidb` has function names in human-readable format.

The generated databases may contain duplicates or conflicts.

Functions were demangled with [this script](https://gitlab.com/yakovlevegor/BorlandCPPDemangler).
