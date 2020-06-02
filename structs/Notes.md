# A bit on module installation
- Exported structs/methods start with a capital letter. Unexported otherwise.
- Initing a Go module by using: `go mod init module_name`.

## init function:
- The init function must not have any return type and it must not have any parameters.
- The init function cannot be called explicitly in our source code.

- The order of initialization of a package is as follows
    + Package level variables are initialised first
    + `init` function is called next. A package can have multiple init functions (either in a single file or distributed across multiple files) and they are called in the order in which they are presented to the compiler.