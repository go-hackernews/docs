# hackernews

A pure-Go, dependency-free client for the official Hacker News Firebase API (`https://hacker-news.firebaseio.com/v0/`). Fetch individual items, users and the top / new / best / ask / show / job story lists. `CGO_ENABLED=0` for static binaries on every platform, standard library only (`net/http`, `encoding/json`, `context`), 100% test coverage with `net/http/httptest` (no network access).

## Install

```bash
go get github.com/go-hackernews/hackernews
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-hackernews/hackernews>
- API reference: <https://pkg.go.dev/github.com/go-hackernews/hackernews>

!!! note
    See the module's README for full, up-to-date details.
