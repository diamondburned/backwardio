# [backwardio](https://pkg.go.dev/github.com/diamondburned/backwardio)

Package backwardio implements a buffered scanner that scans backwards.

### Test Coverage

```
―❤―▶ go test -coverprofile=/dev/null
PASS
coverage: 100.0% of statements
ok  	github.com/diamondburned/backwardio	0.002s
```

## Why

This is useful for parsing logs or files of line-delimited JSON from the latest
entry first.

### Actually, why?

Because I wrote this library for that purpose, realized I don't need it anymore,
and now I'm making it a library so I don't feel like I wasted my time.
