---
title: Software
---

# CuraEngine

Building libArcus 3.1.0 for CuraEngine 3.1.0 can be done with:

```
wget https://github.com/ismangil/libArcus/archive/3.1.0.tar.gz

tar zxvf 3.1.0.tar.gz

cd 

mkdir build && cd build

cmake .. -DBUILD_PYTHON=OFF -DBUILD_EXAMPLES=OFF

make

sudo make install
```


​