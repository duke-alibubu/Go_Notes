# Variadic Functions
- Func notation example: `func f(nums ...int)`
- Remember that variadic parameters need to be the final params (...last in the param list)

## How it works beneath
- The way variadic functions work is by converting the variable number of arguments to a slice of the type of the variadic parameter. 

## Passing a slice to a variadic func
- Have to suffice the slice with `...`.
- Since we passed as a slice, the slice passed to the variadic func will reflect its change.