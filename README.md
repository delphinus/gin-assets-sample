*This is written for [this issue][issue].*

[issue]: https://github.com/gin-gonic/gin/issues/1316

*Now this is in [`examples` directory][dir] in gin.*

[dir]: https://github.com/gin-gonic/gin/tree/master/examples/assets-in-binary

# gin-assets-sample

This is a complete example to create a single binary with the
[gin-gonic/gin][gin] Web Server with HTML templates.

[gin]: https://github.com/gin-gonic/gin

## How to use

### Prepare Packages

```
go get github.com/gin-gonic/gin
go get github.com/jessevdk/go-assets-builder
```

### Generate assets.go

```
go-assets-builder assets -o assets.go
```

### Build the server

```
go build
```

### Run

```
./go-assets-sample
```
