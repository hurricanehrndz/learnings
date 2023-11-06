.PHONY: test test-by-name

build go-build: bin bin/helloworld
bin/helloworld:
	go build -o bin/helloworld ./cmd/helloworld

bin:
	@mkdir $@

test: test-by-name
test-by-name:
	@gotestsum --format testname

