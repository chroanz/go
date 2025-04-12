# Go Study Repository

This repository contains a collection of Go examples to learn and practice the Go programming language fundamentals and web development.

## Examples

### Language Fundamentals
- **`helloworld.go`** - Basic "Hello, World!" program
- **`values.go`** - Basic types and operations on values
- **`variables.go`** - Variable declaration and initialization
- **`constants.go`** - Constant declaration and usage
- **`for.go`** - Different loop structures in Go
- **`ifelse.go`** - Conditional statements
- **`switch.go`** - Switch statement examples
- **`arrays.go`** - Working with arrays
- **`slices.go`** - Working with slices

### Web Development
- **`main.go`** - Simple HTTP server implementation

## How to Run the Examples

To run any of the Go examples, use the `go run` command:

```bash
go run <filename>.go
```

## API Server

The `main.go` file contains a simple HTTP server that:
- Serves a welcome message at the root route (`/`)
- Serves static files from a `static/` directory
- Listens on port `8080`

When run, you can access the server at [http://localhost:8080](http://localhost:8080).

## Learning Resources

These examples are based on common Go patterns and practices. For more comprehensive learning, consider visiting:
- [Go Documentation](https://golang.org/doc/)
- [Go by Example](https://gobyexample.com/)
- [Tour of Go](https://tour.golang.org/)

## License

This repository is for educational purposes.