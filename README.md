WM git tools
============

Extra tools I use for working with git.


## Tools

### wmrepostatus

Check the status of all repositories in `~/.wmrepositories`.

    $ cat ~/.wmrepositories
    repos = [
        ("Repo1 name", "/Path/to/repo1"),
        ("Repo2 name", "/Path/to/repo2")
    ]
    $ ./wmrepostatus
    Repo1 name (origin/master) ................ +5
    Repo2 (master) ............................ *1

Meaning of symbols:

- **+5**: Local repository is ahead with 5 commits
- **-3**: Remote repository is ahead with 3 commits
- **\*1**: Repository has 1 file with not committed changes




## Contact

**Main contact**  
Wannes Meert  
Department of Computer Science  
K.U.Leuven  
Celestijnenlaan 200A  
3001 Heverlee (Leuven)  
<http://people.cs.kuleuven.be/wannes.meert>
<wannes.meert@cs.kuleuven.be>


## License

The Lesser GNU Public License, Version 3.0  
http://www.gnu.org/licenses/lgpl-3.0.txt

Copyright (c) 2011, K.U.Leuven. All rights reserved.

