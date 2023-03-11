# webassembly

cd cmd/server
GOOS=js GOARCH=wasm go build -o main.wasm main.go
go run main.go

Open assets/index.html and verify wasm module via page inspection. 
