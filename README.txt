# BCrawler
A folder crawler in python3

**Installation for Linux**

```
 ~ ❯❯❯ sudo python3 setup.py install
```

**Installation for Windows**

```
 ~ ❯❯❯ python3 setup.py install
```


## How to use / Documentation

### your_app.py
```
from bcrawler import *

files = bcrawler.crawl('path/of/your/folder')
#type(files) = list

print(files)

```
