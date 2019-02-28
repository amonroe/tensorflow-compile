# tensorflow-compile
Tensorflow wheel for Python 3.7 but without AVX support for running on less capable CPUs.  This was compiled on a Celeron J4105.  

You can install using:
```
pip install --ignore-installed --upgrade /path/to/binary.whl
```

| TF    | HW  | OS                | GCC              | Python | Does NOT Support                                            |                                                                                                                                                                                |
|-------|-----|-------------------|------------------|--------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.13.0 | CPU | Ubuntu 18.04      | 8.2              | 3.7.1  | AVX, AVX2                      | [Download](https://github.com/amonroe/tensorflow-compile/blob/master/tensorflow-1.13.0-cp37-cp37m-linux_x86_64.whl?raw=true)   


The Dockerfile used to build is available as well if you'd prefer to build your own.  It was derived from tensorflow build process.
