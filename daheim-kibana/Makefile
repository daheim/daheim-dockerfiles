
all: release

build:
	docker build -t egergo/daheim-kibana:latest .

release: build
	docker push egergo/daheim-kibana:latest

.PHONY: all build release
