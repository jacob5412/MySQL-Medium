# MySQL Medium

## Fixing “my_config.h” file not found in MySQL-python (Mac OS)

```bash
_mysql.c:44:10: fatal error: 'my_config.h' file not found
    #include "my_config.h"
             ^~~~~~~~~~~~~
    1 error generated.
    error: command 'gcc' failed with exit status 1
```

Article can be found on [medium](https://medium.com/the-rising-tilde/fixing-my-config-h-file-not-found-in-mysql-python-mac-os-ff97663a8042)

This repo contains the required `my_config.h` header to fix the issue.