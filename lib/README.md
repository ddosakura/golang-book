# golang-book

Golang Collection
Golang 项目收集（用过的）

## 起源

+ [spf13](https://github.com/spf13)
+ [项目集](https://blog.csdn.net/zzhongcy/article/details/73558218)

## 第一批

+ 检测主目录 `github.com/mitchellh/go-homedir`
+ CLI `github.com/spf13/cobra`
+ 配置读取 `github.com/spf13/viper`
    + yaml `gopkg.in/yaml.v2`
+ 文件系统 `github.com/spf13/afero`
+ 静态资源 `github.com/rakyll/statik`
    + 多实例解决方案 [sblock](https://github.com/ddosakura/sblock)
    + Or [statik#56](https://github.com/rakyll/statik/issues/56)
+ 文件监控 `gopkg.in/fsnotify/fsnotify.v1`
+ 压缩文件 `github.com/mholt/archiver`

## 第二批

+ [ ] 终端UI `github.com/nsf/termbox-go`
+ [ ] 终端UI `github.com/gizak/termui` (原项目API变动中，使用`gopkg.in/gizak/termui.v2`)
+ [ ] 终端彩虹输出 `github.com/arsham/rainbow/rainbow`
+ [x] 结构查看 `github.com/davecgh/go-spew/spew`
+ [ ] 写web handler(URL router and dispatcher) `github.com/gorilla/mux`
+ [x] 加载环境变量 `github.com/joho/godotenv`
+ [x] 读取环境变量 `github.com/timest/env`
+ [x] 自动化系统 `github.com/go-vgo/robotgo`
+ [ ] 二维码生成 I `github.com/skip2/go-qrcode`
+ [ ] 二维码生成II `github.com/boombuler/barcode`
+ [ ] 二维码识别 `github.com/tuotoo/qrcode`
+ [x] 二维码输出到终端 `github.com/qianlnk/qrcode` (不好使)

