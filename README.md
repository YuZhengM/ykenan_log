# ykenan_log

> **`Print and save a simple log to a file`**

```shell
pip install --upgrade build -i http://pypi.douban.com/simple --trusted-host pypi.douban.com
pip install --upgrade twine -i http://pypi.douban.com/simple --trusted-host pypi.douban.com
```

```shell
py -m build
twine check dist/*
twine upload dist/*
```

## Use

> install

```shell
pip install coloredlogs
pip install ykenan_log
```

> use

```python
# -*- coding: utf-8 -*-

import ykenan_log

logger = ykenan_log.Logger("log")

if __name__ == '__main__':
    print("run...")
    logger.debug("info......")
    logger.info("info......")
    logger.warn("info......")
    logger.error("info......")
```

![img.png](img.png)
