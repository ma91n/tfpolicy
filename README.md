# tflint
tflint is developper tools for terraform style check linter.

# Status


# For Example

```
$ go run main.go
2019/04/28 22:57:32 2 errors occurred:
	* [ERROR] \testdata\example.tf: resource label must match pattern [a-zA-Z]+-[a-zA-Z]+: label='sql',type='mst_db'
	* [ERROR] \testdata\example.tf: resource label must match pattern [a-zA-Z]+-[a-zA-Z]+: label='sql',type='ope_db'
```

