# gradients
% go install google.golang.org/grpc/cmd/protoc-gen-go-grpc
% protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative gradients.proto
