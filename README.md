## Download/Install

```bash
$ git clone github.com/stishenok/go-tools
$ cd go-tools/cmd/goimports
$ go install

$ export ORG=github.com/karhoo
(add in ~/.bash_profile)
$ goimports -w -local=github.com/karhoo/int-fasttrak .
local - current package (repository)
```