Check python platform information in runtime-safe way

```Python
import oscheck

if oscheck.family() == oscheck.OS_LINUX:
  do_some_staff()
elif oscheck.family() == oscheck.OS_WINDOWS:
  do_other_staff()

...
```
