# infoway-tx
Experimental repository for Infoway-managed terminology. Not for public consumption.

This repository contains
* tx.1 - an IG that contains a single large valueset
* tx.2 - an IG that contains a single medium-sized value set
* tx.3 - an IG that contains a single medium-sized value set
* tx - an IG that contains multiple smaller value sets, and is dependent on tx.1, tx.2, and tx.3
* term - a standalone IG containing all the terminology contained in tx, tx.1, tx.2, and tx.3

Sample build times:
IG | Build time (min)
--- | ----------
 tx.1 | 26:38
 tx.2 | 7:19
 tx.3 | 5:19
 tx | 1:27
**tx total** | **40:43**
**term**| **1:41:43**

Note that *_genonce.sh* scripts have been edited to give 8GB heap space to the publisher.
