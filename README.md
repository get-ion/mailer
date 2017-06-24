# Mailer

Simple E-mail sender.

[![Build status](https://api.travis-ci.org/get-ion/mailer.svg?branch=master&style=flat-square)](https://travis-ci.org/get-ion/mailer)

## Installation

```sh
$ go get github.com/get-ion/mailer
```

## Docs

- `New` returns a new, e-mail sender service.
- `Send` send an e-mail, supports text/html and `sendmail` unix command
```go
Send(subject string, body string, to ...string) error
```

## Table of contents

* [Overview](_example/main.go)

## Contributing

If you are interested in contributing to this project, please push a PR.

## People

[List of all contributors](https://github.com/get-ion/mailer/graphs/contributors)
