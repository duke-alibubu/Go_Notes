# Array
- Is of FIXED size. Passed as value, not reference!!!!
# Slices
- Like, a reference to an array. Passed as reference.
- The length of the slice is the number of elements in the slice.
- The capacity of the slice is the number of elements in the underlying array starting from the index from which the slice is created.
- Initialization without a size is considered a slice initialization. (E.g: `[]string` is a slice, but `[2]string` is an array)