# Variadic Function
In Go for setting function argumanets in variadic functions, we can use these syntax.

```go
func sum(nums ...int) int {
	total := 0
	for _, v := range nums {
		total := total + v
	}
	return total
}
```
# 1
to setting the value we can use this syntax.
```go
total := sum([]int{1, 3, 5, 7, 9})
```
# 2
In this Format we should put `...` after the variable name.
```go
nums := []int{2, 4, 60, 10}
total := sum(nums...)
```

