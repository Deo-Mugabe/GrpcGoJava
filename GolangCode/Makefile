gen: 
	protoc --proto_path=proto --go_out=pb --go-grpc_out=pb proto/*.proto

clean:
	rm -rf pb/*

run:
	go run main.go