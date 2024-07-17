.DEFAULT_GOAL := build

.PHONY: vet build
fmt:
	go fmt ./...

vet: fmt
	go vet ./...

build: vet
	go build

clean:
	rm -f exercise_1