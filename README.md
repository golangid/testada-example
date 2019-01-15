# testada-example

This repository is just an example how to do integration testing in Golang with a real Database. An example usage from [github.com/golangid/testada](https://github.com/golangid/testada) package.


## How To Run The Test

Prerequisite:
- Docker (docker-compose)
- go 1.11+
- Unix environment 

Locally:

```shell

$ make integration-test
# Will run the integration testing of this projects. Wait until finished.

$ make clear
# After finished, clear all the testing dependencies
```
