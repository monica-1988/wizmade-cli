# wizmade-cli

A small command-line helper for [Wizmade](https://wizmade.si/), an AI image and video creation studio.

Prints a short product description and the homepage URL. It does not generate
images or videos, upload files, or call an API.

## Run from source

Requires Go 1.22 or later.

```sh
go run .
```

Output:

```text
Wizmade - AI image and video creation studio
Homepage: https://wizmade.si/
```

## Build

```sh
go vet ./...
go build .
```

Remote installation and pkg.go.dev indexing are pending repository publication.

## License

MIT. See [LICENSE](LICENSE).
