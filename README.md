# Go-basics
The basics of Go. To be used as a reference to look back on

[![Generic badge](https://img.shields.io/badge/go-1.21.2-<COLOR>.svg)](https://shields.io/) 
[![GitHub license](https://badgen.net/github/license/AndyDHaines/go-basics)](https://github.com/AndyDHaines/go-basics/blob/main/LICENSE) 
[![GitHub branches](https://badgen.net/github/branches/AndyDHaines/go-basics)](https://github.com/AndyDHaines/go-basics/) 
[![GitHub latest commit](https://badgen.net/github/last-commit/AndyDHaines/go-basics)](https://github.com/AndyDHaines/go-basics/commits/)

## Go Homepage
[https://go.dev/](https://go.dev/)

## Basics
At a high level the term for a project within Go is a module. To initialise a new Go module there are two main steps

1. Create a folder on disk where you want the module to live
2. Run the following command from within the newly created folder

```
go mod init MODULE_NAME
```

## Functions
A function declaration looks like this
```
func Add(a, b float64) float64 {
    return a + b
}
```



