# lab6

A single C source file, `helloworld.c`, printing `Hello World!` to stdout.

## Build and run

```
gcc helloworld.c -o helloworld
./helloworld
```

## Note on the exit code

`main` returns `1` rather than `0`. On POSIX systems a non-zero exit status
signals failure, so the shell reports this program as having failed even though
it printed correctly. Check it with `echo $?` after running.
