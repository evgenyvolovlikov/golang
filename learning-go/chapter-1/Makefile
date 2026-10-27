.DEFAULT_GOAL := build

.PHONY: fmt vet build all

fmt:
	go fmt ./...

vet:
	go vet ./...

build: fmt vet
	go build ./...

clean:
	go clean

all: fmt vet build
