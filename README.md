# dockerfile


## sqlcli

### Oracle

將 [SQLcl](http://www.oracle.com/technetwork/developer-tools/sqlcl/overview/index.html) 打包成 docker

How to use

```
$ docker run -it --name sqlcli sldennis/sqlcli ./bin/sql
SQLcl: Release 17.3.0 Production on Fri Nov 03 10:17:30 2017

Copyright (c) 1982, 2017, Oracle.  All rights reserved.

/bin/bash: tput: command not found
/bin/bash: tput: command not found
Username? (''?) {username}@{ip}:{port}:{DB}
Password? (**********?) ******
```
