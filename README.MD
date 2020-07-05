## Example of how to containerise processes dependant on terminal emulation

build base image

```
cd 3270Containerimage
docker build petebids/3270:v1
```

build an application from the base image
```
cd Example3270App
docker build me/myapp:v1
```
