REPOSITORY = ysakashita/nginx
TAG = 191004

.PHONY: build container push

all: build

build: container

container:
	docker build -t $(REPOSITORY):$(TAG) .

push: container
	docker push $(REPOSITORY):$(TAG)
