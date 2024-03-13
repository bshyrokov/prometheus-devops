# TODO List
### 1. Investigate and fix issue with "RUN CGO_ENABLED=1 go build -o app"
```bash
 57.77 See <file:///usr/share/doc/gcc-12/README.Bugs> for instructions.
------
Dockerfile:5
--------------------
   3 |     COPY src .
   4 |     #RUN CGO_ENABLED=1 go build -o app
   5 | >>> RUN go build -o app
   6 |     
   7 |     FROM scratch 
--------------------
ERROR: failed to solve: process "/bin/sh -c go build -o app" did not complete successfully: exit code: 1
```

### 2. Investigate and fix issue with slider/carousel svgs
### 3. Prepare step by step instructions for coding sessions
### 4. To ask Denys about tests for python in the webform