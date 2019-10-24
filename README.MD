### support a way to access go internal package

#### example.
```go
s, _ := os.Executable()
file, _ := objfile.Open(s)
syms, _ := file.Symbols()
fmt.Println(len(syms))
```