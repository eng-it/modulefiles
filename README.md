# modulefiles
[Module files] for managing user environments on the BU Engineering Grid.

Example usage:

    $ which python
    /usr/bin/python
    $ module whatis anaconda
    anaconda             : Anaconda Scientific Python Distribution
    $ module load anaconda
    $ which python
    /ad/eng/opt/64/anaconda-2.0.1-py27/bin/python
    $ module unload anaconda
    $ which python
    /usr/bin/python

For instructions on creating a module file, see the [add a shell module]
section of EXAMPLE.md in the [linux-builds] repository.

[Module files]: http://modules.sourceforge.net/
[linux-builds]: https://github.com/eng-it/linux-builds
[add a shell module]: https://github.com/eng-it/linux-builds/blob/master/EXAMPLE.md#add-a-shell-module
