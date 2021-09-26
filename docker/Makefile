VERSION=0.0.69
PROJECT_ID=jankul02
PROJECT=${PROJECT_ID}

all: build

build:
	docker build --pull -t ${PROJECT}/kubernetes-kafka:${VERSION} .

push: build
	docker push ${PROJECT}/kubernetes-kafka:${VERSION}

.PHONY: all build push
