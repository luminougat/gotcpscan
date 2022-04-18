# GoTcpScan

Simple TPC port scanner written in Go.

Build:

```
# Windows x64 executable
GOOS=windows GOARCH=amd64 go build -o gotcpscan.exe main.go

# Windows x86 executable
GOOS=windows GOARCH=386 go build -o gotcpscan.exe main.go

# Linux x64 executable
GOOS=linux GOARCH=amd64 go build -o gotcpscan main.go

# Linux x86 executable
GOOS=linux GOARCH=386 go build -o gotcpscan main.go
```
