VERSION ?= latest

.PHONY: build
build:
	docker build -t replicated/kots-idp-example-app:$(VERSION) .
	docker tag replicated/kots-idp-example-app:$(VERSION) replicated/kots-idp-example-app:latest

.PHONY: push
push:
	docker push replicated/kots-idp-example-app:$(VERSION)
	docker push replicated/kots-idp-example-app:latest
