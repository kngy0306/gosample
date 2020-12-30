# gosample

[Goのプロジェクト構成とパッケージ](https://gihyo.jp/dev/feature/01/go_4beginners/0001?page=3)

# Usage

```
$ cd $GOPATH/src
$ go get github.com/kngy0306/gosample
```

```go
package main

import (
	"fmt"
	"github.com/kngy0306/gosample"
)

func main()  {
	fmt.Println(gosample.Message)
}
```
