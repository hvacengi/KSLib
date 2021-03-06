# HOW TO USE THIS

The KSlib repository is a place you can obtain useful examples
created by past contributors, be they users of the kOS mod,
or in some cases the oiginal developers of the kOS mod.

Due to a limitation in the current implementation of kOS, all
kerboscript files have to live in the same directory, so when
you copy these files you'll have to put them all in the same 
place with no heirarchy.

For the time being, just read the examples and copy the files
you want to use into your Ships/Scripts directory of your
Kerbal Space Program installation and use them from there.

We do ask that for people submitting a suite of libraries
designed to work together, that they try to follow these
general patterns:

  1. Try to break things up into smaller files.  A person trying
     to load them onto their installation may be trying to save
     space and want to only install those things they need.
  2. Try to include an example of how to use the files when you
     submit them.  Put the examples in the example folder and
     the actual library files they call in the library folder.

## Project Folder Layout:

  * library/
    * The place where the actual .ks files people can copy into their
      own installations go.
  * examples/
    * The place where examples of scripts that call a library function
      can go.
  * doc/
    * A place for you to describe your library and how to use it, in
      textual form, using ascii text, or Github markdown files (.md).
