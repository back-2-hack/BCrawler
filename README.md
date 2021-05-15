# BCrawler
A folder crawler library in python3

<br/>

## Installation
**For Linux**

```

 ~ ❯❯❯ git clone https://github.com/back-2-hack/BCrawler.git
 
 ~ ❯❯❯ cd  BCrawler
 
 ~ ❯❯❯ sudo pip3 install -r requirements.txt
 
 ~ ❯❯❯ sudo python3 setup.py install
```

**For Windows**

```
 ~ ❯❯❯ git clone https://github.com/back-2-hack/BCrawler.git
 
 ~ ❯❯❯ cd  BCrawler
 
 ~ ❯❯❯ pip3 install -r requirements.txt

 ~ ❯❯❯ python3 setup.py install
```

<br/>
<br/>

## Installation with pip

**For Linux**

```
 ~ ❯❯❯ sudo pip3 install BCrawler
```

**For Windows**

```
 ~ ❯❯❯ pip3 install BCrawler
```

<br/>
<br/>

## How to use / Documentation

### your_app.py
```
from bcrawler import *

files = bcrawler().crawl('path/of/your/folder')

print(files)

```
### Output

```
['file1.x','file2.x']
```
