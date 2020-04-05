# chimera-debian
Debian meta files for Chimera

## Update `changlog` files using a script

Set following environment variables that are used in the changelog files:
```
$ export DEBEMAIL=<your_email>        # e.g., export DEBEMAIL=jslee02@gmail.com
$ export DEBFULLNAME=<your_fullname>  # e.g., export DEBEMAIL=Jeongseok Lee
```

To update changelogs and push a commit for the changes, run:
```
$ ./changelog_spawn.sh <new_version>  # e.g., ./changelog_spawn.sh 1.0.0-0
```