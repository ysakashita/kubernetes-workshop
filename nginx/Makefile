REPOSITORY := ysakashita/my-nginx
TAG := latest

.PHONY: build push

build:
	docker build -t $(REPOSITORY):$(TAG) .

push: build
	docker push $(REPOSITORY):$(TAG)
