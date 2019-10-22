# GitChangelog

[![GoDoc](https://godoc.org/github.com/nickanderegg/gitchangelog?status.svg)](https://godoc.org/github.com/nickanderegg/gitchangelog)
[![Build Status](https://travis-ci.org/nickanderegg/gitchangelog.svg)](https://travis-ci.org/nickanderegg/gitchangelog) [![Build status](https://ci.appveyor.com/api/projects/status/c8tu1wdoa4j7q81g?svg=true)](https://ci.appveyor.com/project/bjornerik/gitchangelog)
[![Go Report Card](https://goreportcard.com/badge/github.com/nickanderegg/gitchangelog)](https://goreportcard.com/report/github.com/nickanderegg/gitchangelog)
[![codecov](https://codecov.io/gh/nickanderegg/gitchangelog/branch/master/graph/badge.svg)](https://codecov.io/gh/nickanderegg/gitchangelog)

A fairly fast way to create a map from all the filenames to info objects for a given revision of a Git repo.

This library uses `os/exec` to talk to Git. There are faster ways to do this by using some Go Git-lib or C bindings, but that adds dependencies I really don't want or need.

If some `git log kung fu master` out there have suggestions for improvements, please open an issue or a PR.
