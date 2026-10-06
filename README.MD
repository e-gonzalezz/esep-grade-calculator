# ESEP Grade Calculator

This library is a simple utility to calculate a student's final grade. Grades are added as assignments, exams, or essays. Each type is averaged, then combined as a weighted sum to produce a numerical grade, which is then converted to a letter grade.

## Tech Stack
- Language: Go (Golang)
- Build management: Go modules (`go.mod`)
- Testing: Go's built-in `testing` package and `go test` tool

*Runtime requirements:*
- Golang 1.24+ (check your version with `go version`)

## Project

- `grade-calculator/grade_calculator.go`: the calculator
- `grade-calculator/grade_calculator_test.go`: unit tests
- `grade-calculator/go.mod`: module definition

## Run Unit Tests: 
```
cd grade-calculator/
go test ./...
```

## Run Unit Tests With Code Coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```