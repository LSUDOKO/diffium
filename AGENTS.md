# diffium

Diffium is a CLI tool to help you better understand git diffs, with the main intention to make co-development with AI coding agents easier.

## Commands

- build: `go build ./...`
- test: `go test ./...`

## Layout

- `cmd/`
- `internal/`
- `nvim-plugin/`
- `releases/`

## Rules

- Run `go test ./...` before you say a change is done.
- Never commit secrets or `.env` files.
