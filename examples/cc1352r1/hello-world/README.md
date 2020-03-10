A minimal Contiki-NG example, simple printing out "Hello, world".
This example runs nullnet and nullmac and has been modified to rename the output .hex and .bin with a description.
To compile execute:

```
make clean && make DESCR=cc1352r1-test node.rename
```

The contiki-ng repo version is of :

```
commit f400fbe96e76c637772487b76ac00941e40bbf50
```
Date:
```
Fri Mar 6 20:27:01 2020
```