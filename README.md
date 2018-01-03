# Line Bot - Emotion list

> Golang emotion lib for Line Bot - Update at 03/01/2018.

## Installation

As a library

```shell
go get github.com/gokusenz/line-bot-emotion-list/runeList
```

## Usage

```go
package main

import (
    "github.com/gokusenz/line-bot-emotion-list"
    "log"
)

func main() {
  message := "0x10002D 0x100077 LINE EMOTION FOR LINE-BOT"
  message = runeList.CheckRune(message)
  log.Println(message)

}
```
