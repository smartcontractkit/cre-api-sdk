.PHONY: generate
generate:
	version=$$(go list -m -f '{{.Version}}' github.com/gqlgo/gqlgenc) && \
	go run github.com/gqlgo/gqlgenc@$$version generate
