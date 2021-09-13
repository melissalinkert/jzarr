# JZarr

A Java version of the API offered by the wonderful Python [zarr](https://zarr.readthedocs.io/) package.


This API also uses blosc compression. To use this compression, a compiled c-blosc distributed library must be available on the operating system. 
If such a library is not available ... The C sourcecode and instructions to build the library can be found at https://github.com/Blosc/c-blosc.
If you want to use the JZarr API and the integrated blosc compression, you have to start the Java Virtual Machine with the following VM parameter:

    -Djna.library.path=<path which contains the compiled c-blosc library>

## Documentation
You can find detailed information at [JZarrs project documentation](https://jzarr.readthedocs.io) page.  


## Build Documentation
The projects documentation is automatically generated and provided using "Read the Docs".
Some files, needed to build the "**read the docs**" documentation must be generated to be up to
date and along with the code. Therefor a class has been implemented which searches for
classes whose filename ends with "_rtd.java" and invokes whose **`main`** method.
Rerun the class (**`ExecuteForReadTheDocs`**) to autogenerate these
referenced files.

## Snapshot versions

Snapshot versions have been deployed to https://repo.glencoesoftware.com/repository/jzarr-snapshots/, and correspond to the following commits:

Snapshot version                                | Commit
------------------------------------------------|-----------------------------------------------------------------------------------------
0.3.3-gs-SNAPSHOT/0.3.3-gs-20210224.144307-1	| https://github.com/glencoesoftware/jzarr/commit/4341973a9c6076b795dabef0ff05f088b0c41215
0.3.3-gs-SNAPSHOT/0.3.3-gs-20210224.144924-2	| https://github.com/glencoesoftware/jzarr/commit/4341973a9c6076b795dabef0ff05f088b0c41215
0.3.3-gs-SNAPSHOT/0.3.3-gs-20210412.092346-3	| https://github.com/glencoesoftware/jzarr/commit/0be6d3a7a8a2447dcbaca1783a91ddf9867684f9
0.3.3-gs-SNAPSHOT/0.3.3-gs-20210426.125901-4	| https://github.com/glencoesoftware/jzarr/commit/6db9f5e6134a2a9813ac5e70b0392f0e8ba190b3
