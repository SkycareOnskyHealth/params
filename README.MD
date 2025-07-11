# Params Helper

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://github.com/SkycareOnskyHealth/params)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/SkycareOnskyHealth/params)

Params parser helper.

## Getting Started!

> Convert string of params to slice of integer
```
	result, err := ConvertToInt(param, sep)
	if err != nil || result == nil {
		t.Fatal("convert error")
	}
```

> Convert string of params to slice of string
```
	result, err := ConvertToString(param, sep)
	if err != nil || result == nil {
		t.Fatal("convert error")
	}
```

### Installation

Request handler requires [Go](https://golang.org/) v1.11+ to run.

Install the package.

```sh
$ go get github.com/SkycareOnskyHealth/params
```

#### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


### Todos

 - Write MORE Tests
 - Add Night Mode

License
----

MIT