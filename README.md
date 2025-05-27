# BF (BrainFuck)
Shortest Golang Brainfuck Interpreter implementation.
# Usage
```go
package main

import "os"
import "github.com/nikdissv-forever/bf"

func main() {
	if f, e := os.ReadFile(os.Args[1]); e == nil {
		B.R(f)
	}
}
```
Released CLI version
> bf[.exe] hw.bf