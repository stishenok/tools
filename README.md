# Go Tools

## Changes
1. Organization defined in the ENV variable ORG is grouped separately.
2. Ignore user defined empty lines between imports.
3. If few packages are provided in `local`, the each group will be intended with new line.

## Download/Install

```bash
$ git clone https://github.com/stishenok/tools.git
$ cd tools/cmd/goimports
$ go install

$ export ORG=github.com/karhoo
(add in ~/.bash_profile or ~/.zshrc)

$ goimports -w -local=github.com/karhoo/svc-money .
local - current package (repository)
```