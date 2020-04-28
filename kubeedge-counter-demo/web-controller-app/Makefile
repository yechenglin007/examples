.PHONY: all build kubeedge-counter-controller docker clean

all:build

build:kubeedge-counter-controller

kubeedge-counter-controller:
	go build -o kubeedge-counter-controller main.go

docker:kubeedge-counter-controller
	docker build . -t kubeedge/kubeedge-counter-app:v1.0.0

clean:
	rm -rf ./kubeedge-counter-controller
