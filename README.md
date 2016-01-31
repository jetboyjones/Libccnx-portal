Libccnx-common
=======

The CCNx Common Library
==========

## Introduction ##

This is a library of CCNx functions and data structures.

## Overview ##

For a full CCNx software distribution please look at the CCNx Distillery
https://github.com/PARC/CCNx_Distillery

## Dependencies ##

This library depends on LongBow. 
- https://github.com/PARC/LongBow
- https://github.com/PARC/Libparc

## Getting Started ##

Build and install LongBow by executing
```
mkdir build
cd build
cmake ..
make
make install
make test
```

This will create the `include` and `lib` directories containing the necessary files to compile with LongBow.

### Contact ###

Please see http://www.ccnx.org/

### License ###

This software is distributed under the following license:

```
Copyright (c) 2013, 2014, 2015, 2016, Xerox Corporation (Xerox)and Palo Alto
Research Center (PARC)
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright
  notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright
  notice, this list of conditions and the following disclaimer in the
  documentation and/or other materials provided with the distribution.
* Patent rights are not granted under this agreement. Patent rights are
  available under FRAND terms.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL XEROX or PARC BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```