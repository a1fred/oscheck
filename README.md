[![PyPI version](https://badge.fury.io/py/oscheck.svg)](https://badge.fury.io/py/oscheck)
[![Build Status](https://travis-ci.org/a1fred/oscheck.svg?branch=master)](https://travis-ci.org/a1fred/oscheck)
[![Coverage Status](https://coveralls.io/repos/github/a1fred/oscheck/badge.svg?branch=master)](https://coveralls.io/github/a1fred/oscheck?branch=master)


Check python platform information in runtime-safe way

```Python
import oscheck

if oscheck.family() == oscheck.OS_LINUX:
  do_some_staff()
elif oscheck.family() == oscheck.OS_WINDOWS:
  do_other_staff()

...
```
