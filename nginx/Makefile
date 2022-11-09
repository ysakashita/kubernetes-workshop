REPOSITORY = ysakashita/my-nginx
export: TAG := latest

.PHONY: build container push

all: build

build:
	docker build -t $(REPOSITORY):$(TAG) .

push: container
	docker push $(REPOSITORY):$(TAG)
