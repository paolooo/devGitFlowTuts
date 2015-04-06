# Git Flow


## 1. Initial commit

master  = *

#### Files

* README.md
* index.php

----

## 2. Create a develop branch

```bash
$ git checkout -b develop
```
master  = *
           \
develop =   *

##### Files on develop is the same as on master

* README.md
* index.php

## 3. Added header and footer files.

master  = *
           \
develop =   *--*(a)--*(b)--*(c)

a. Modified index.php and added header.php
b. Modified index.php and added footer.php
c. Modified README.md

##### Files on develop branch

* README.md
* index.php
* header.php
* footer.php
