REPOSITORY = ysakashita/my-nginx
TAG = 20221107

.PHONY: build container push

all: build

build:
	docker build -t $(REPOSITORY):$(TAG) .

push: container
	docker push $(REPOSITORY):$(TAG)
