# gen-tools

> a bunch of packages u may need if u're writing code generation

It contains:
- [mockgen](github.com/golang/mock/blob/main/mockgen) fricassee (part for parsing src go file into [model.Package](./mockgen/model/model.go) which was some kind of vendored)
- [strtools](./strtools) for making your string in different cases (camel | snake)
- [fwriter](./fwriter) for saving your generated code with overwrite cli options
- [clogger](./clogger) for colorful logging into cli

That's actually all i needed
