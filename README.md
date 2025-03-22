# gen-tools

> a bunch of packages u may need if u're writing code generation

It contains:
- [mockgen](https://github.com/golang/mock/blob/main/mockgen) fricassee (part for parsing src go file into [model.Package](./mockgen/model/model.go) which was some kind of vendored)
- [strtools](./strtools/case.go) for making your string in different cases (camel | snake)
- [fwriter](./fwriter/fwriter.go) for saving your generated code with overwrite cli options
- [clog](clog/logger.go) for colorful logging into cli

That's actually all i needed
