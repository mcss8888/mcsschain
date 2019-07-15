[![pipeline status](https://api.travis-ci.org/33cn/plugin.svg?branch=master)](https://travis-ci.org/33cn/plugin/)
[![Go Report Card](https://goreportcard.com/badge/github.com/33cn/plugin?branch=master)](https://goreportcard.com/report/github.com/33cn/plugin)


# 基于 chain33 区块链开发 框架 开发的 mcsschain公有链系统


### 编译

```
git clone https://github.com/mcss8888/mcsschain $GOPATH/src/github.com/mcss8888/mcsschain
cd $GOPATH/src/github.com/mcss8888/mcsschain
go build -i -o mcsschain
go build -i -o mcsschain-cli github.com/mcss8888/mcsschain/cli
```

### 运行
拷贝编译好的mcsschain, mcsschain-cli, mcsschain.toml这三个文件置于同一个文件夹下，执行：
```
./mcsschain -f mcsschain.toml
```
