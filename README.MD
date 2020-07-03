## Example of how to containerise processes dependant on terminal emulation

build base image

```console
user@machine:~$ cd 3270Containerimage
user@machine:~$ docker build petebids/3270:v1
```

build an application from the base image
```console
user@machine:~$ cd Example3270App
user@machine:~$ docker build me/myapp:v1
```
