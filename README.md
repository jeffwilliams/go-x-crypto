# Go Cryptography

[![Go Reference](https://pkg.go.dev/badge/golang.org/x/crypto.svg)](https://pkg.go.dev/golang.org/x/crypto)

This repository holds supplementary Go cryptography libraries. This (jeffwilliams) version has been modified to add the fix for https://github.com/golang/go/issues/67152 created by Nicola Murino, found at https://go-review.googlesource.com/c/crypto/+/562756

## Download/Install

The easiest way to install is to run `go get -u golang.org/x/crypto/...`. You
can also manually git clone the repository to `$GOPATH/src/golang.org/x/crypto`.

## Report Issues / Send Patches

This repository uses Gerrit for code changes. To learn how to submit changes to
this repository, see https://golang.org/doc/contribute.html.

The main issue tracker for the crypto repository is located at
https://github.com/golang/go/issues. Prefix your issue with "x/crypto:" in the
subject line, so it is easy to find.

Note that contributions to the cryptography package receive additional scrutiny
due to their sensitive nature. Patches may take longer than normal to receive
feedback.
