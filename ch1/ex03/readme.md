## Exercise 1.3

iExperiment to measure the difference in running time between our
potentially inefficient versions and the one that uses
`strings.Join`.(Section 1.6 illustrates part of the `time` package, and
Section 11.4 shows how to write benchmark tests for systematic
performance evaluation.)

## Test

`go test` or
`go test -bench .`

```
$ go test -bench .
PASS
BenchmarkEcho1-4            2000            529430 ns/op
BenchmarkEcho2-4            3000            457801 ns/op
BenchmarkEcho3-4          100000             20405 ns/op
BenchmarkEcho4-4           10000            184312 ns/op
ok      _/Users/nick/Dropbox/Documents/gopl     6.742s
```
