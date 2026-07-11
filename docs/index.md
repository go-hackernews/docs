# go-hackernews

Pure-Go client for the official Hacker News Firebase API.

go-hackernews is a pure-Go, dependency-free client for the official Hacker News Firebase API (`hacker-news.firebaseio.com/v0/`). It reads items (stories, comments, jobs, polls), users and the live story lists. CGO_ENABLED=0 builds static binaries everywhere, tests are network-free, and it cross-compiles to every 64-bit Go target.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target. Licensed BSD-3-Clause.

## Packages

<div class="pk-grid" markdown>
<a class="pk-card" href="packages/hackernews.md"><code>hackernews</code><br><small>Pure-Go client for the official Hacker News Firebase API. CGO=0, zero third-party deps.</small></a>
</div>
