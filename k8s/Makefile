

all: deployment service ingress

KC = microk8s kubectl


importimage:
	docker save content-server > content-server.tar
	microk8s ctr image import content-server.tar 
	microk8s ctr images ls

deployment:
	$(KC) apply -f deployment.yaml

service:
	$(KC) apply -f service.yaml

ingress:
	$(KC) apply -f ingress.yaml

