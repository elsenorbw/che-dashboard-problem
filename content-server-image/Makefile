


all: dockerimage


dockerimage:
	docker build -t content-server .

demo:
	docker run --name content-server -d -p 1234:8080 content-server

