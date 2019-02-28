# tensorflow-compile
Compiled version of tensorflow with Python 3.7 support but without AVX support for running on less capable CPUs.  This was compiled on a Celeron J4105.  

You can install directly from github using:
```
pip install --ignore-installed --upgrade "Download URL" 
```

| TF    | HW  | OS                | GCC              | Python | Does NOT Support                                            |                                                                                                                                                                                |
|-------|-----|-------------------|------------------|--------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.13.0 | CPU | Ubuntu 18.04      | 8.2              | 3.7.1  | AVX, AVX2                      | [Download](https://github.com/amonroe/tensorflow-compile/blob/master/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl?raw=true)   
