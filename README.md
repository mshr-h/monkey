# monkey
Writing An Interpreter In Go

## Installation

```
go get github.com/mshr-h/monkey
```

## Running REPL

```
cd path/to/mshr-h/monkey
go run main.go
```

Then you'll see the prompt.

```
Hello mshr-h! This is the Monkey programming language!
Feel free to type in commands
>>
```

## Executing the test suite

```
$ go test -v ./...
```

Then you'll see the test result.

```
?       github.com/mshr-h/monkey        [no test files]
=== RUN   TestString
--- PASS: TestString (0.00s)
PASS
ok      github.com/mshr-h/monkey/ast    0.008s
=== RUN   TestNextToken
--- PASS: TestNextToken (0.00s)
PASS
ok      github.com/mshr-h/monkey/lexer  0.006s
=== RUN   TestLetStatements
--- PASS: TestLetStatements (0.00s)
=== RUN   TestReturnStatements
--- PASS: TestReturnStatements (0.00s)
=== RUN   TestIdentifierExpression
--- PASS: TestIdentifierExpression (0.00s)
=== RUN   TestIntegerLiteralExpression
--- PASS: TestIntegerLiteralExpression (0.00s)
=== RUN   TestBooleanExpression
--- PASS: TestBooleanExpression (0.00s)
=== RUN   TestParsingPrefixExpressions
--- PASS: TestParsingPrefixExpressions (0.00s)
=== RUN   TestParsingInfixExpression
--- PASS: TestParsingInfixExpression (0.00s)
=== RUN   TestOperatorPrecedenceParsing
--- PASS: TestOperatorPrecedenceParsing (0.00s)
=== RUN   TestIfExpression
--- PASS: TestIfExpression (0.00s)
=== RUN   TestIfElseExpression
--- PASS: TestIfElseExpression (0.00s)
PASS
ok      github.com/mshr-h/monkey/parser 0.007s
?       github.com/mshr-h/monkey/repl   [no test files]
?       github.com/mshr-h/monkey/token  [no test files]
```

## Reference

- [Writing An Interpreter In Go | Thorsten Ball](https://interpreterbook.com/)
