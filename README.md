# Go

## Commands available to run on Go CLI

| Command | Description |
|---------|-------------|
| `go` | portal to working with all things on our local machine |
| `go build` | compiles a bunch of go source code files |
| `go run` | compiles and executes one or two files |
| `go fmt` | formats all the code in each file in the current directory |
| `go install` |  compiles and "installs" a package |
| `go get` | download the raw source code of someone else's package |
| `go test` | runs any tests associated with the current project |


## How do we run the code in our project?
1. Flip on over to the terminal.
2. Navigate to project directory.
3. Run `go run main.go`

## What does `package main` mean?
You cant think of a package as being like a project or a workspace.
A package is a collection of common source code files.
A package can have many relted files inside of it, each file ending with a file extension of GO.
The only requirement for every file inside a package is that the very first line of each file must declare the package that it belongs to.

Types of packages:
- Excecutable: is one that when compiled spits out an actual runable file or an executable
- Reusable: code dependencies or libraries. We put in a lot of reusable logic or helper functions or stuff that will just help us reuse.

`package main` defines a package that can be compiled and then executed. Must have a func called `main`

## What does `import "fmt` mean?

The import statement is used to give our package (the one we are writing) access to some code that is written, written inside of another package

## What's that `func` thing?

`func` is short for function

## How is the main.go file organized?

// package declaration

```
package main
```

// import other packages that we need

```
import xxx
import yyy
import zzz
```

// declare functions, tell go to do things

```
func main() {
    fmt.Println("hi there!")
}
```