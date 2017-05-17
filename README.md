# rutracker-proxy
GUI-less tool for proxying torrent client announces to blocked in Russia rutracker announcers.
Inspired by oringnal [tool](https://github.com/RutrackerOrg/rutracker-proxy). Automatic proxy
rotation every 5 minutes(configurable).

## Dependencies
* Golang compiler

For ArchLinux:

`pacman -S go`

## Installing
`go install github.com/zhulik/rutracker-proxy`

## Building from sources
Proxy is written in Go, so build steps is ordinary for Go software. Clone the repository and then in it's root directory run

`go get && go build`

## Running

`rutracker-proxy`

## Options

`rutracker-proxy --help`

## TODO
* Binary builds for lazy persons:-)
* Unit tests
* Testing in production

## Contribution
You know;-)