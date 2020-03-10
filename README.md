### Usage
- build docker image locally with the command below
```
docker build -t dice .
```
- run built image (-p XXXX:8888 helps to forward specific port)
```
docker run -v ${PWD}/notebooks:/opt/notebooks dice
```
 
