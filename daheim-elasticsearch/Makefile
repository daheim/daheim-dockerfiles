
all: release

build:
	docker build -t egergo/daheim-elasticsearch:latest .

release: build
	docker push egergo/daheim-elasticsearch:latest

.PHONY: all build release
