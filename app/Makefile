VERSION ?= latest

.PHONY: build
build:
	docker build -t replicatedhq/kots-idp-example-app:$(VERSION) .
	docker tag replicatedhq/kots-idp-example-app:$(VERSION) replicatedhq/kots-idp-example-app:latest

.PHONY: push
push:
	docker push replicatedhq/kots-idp-example-app:$(VERSION)
	docker push replicatedhq/kots-idp-example-app:latest
