.PHONY: all pi-execute-app clean

all: pi-execute-app

pi-execute-app:
	GOARCH=arm64 go build -o pi-counter-app main.go

clean:
	rm -f pi-counter-app
