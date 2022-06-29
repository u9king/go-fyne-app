# Go Fyne App

### Markdown Editor

#### Packaging

```cmd
$ fyne package -appVersion 1.0.0 -name Markdown -appID fyne.markdown -release
```

#### Testing

```cmd
$ go test -v
=== RUN   Test_MakeUI
--- PASS: Test_MakeUI (0.00s)
=== RUN   Test_RunApp
--- PASS: Test_RunApp (0.00s)
PASS
ok      fynemd  0.163s
```

### Gold Watcher

#### Testing

```cmd
$ go test -v
=== RUN   TestGold_GetPrices
--- PASS: TestGold_GetPrices (0.00s)
PASS
ok      gold-watcher    0.157s
```

### Reference

- [Building GUI Applications with Fyne and Go (Golang)](https://www.udemy.com/course/building-gui-applications-with-fyne-and-go-golang/)
