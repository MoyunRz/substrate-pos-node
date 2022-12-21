## 简介
这个项目根据 [Substrate polkadot-v0.9.30 ](https://github.com/paritytech/substrate) 进行的修改

## 共识算法

[substrate babe](https://github.com/paritytech/substrate/tree/master/frame/babe)

## 扩展功能

- [substrate contract](https://github.com/paritytech/substrate/tree/master/frame/babe)

## 环境配置



## 运行

> cargo build --release

### cargo 配置

更换国内源,Cargo 支持更换 crates.io 源索引，通过 `$HOME/.cargo/config` 文件配置
```shell
`vim $HOME/.cargo/config`
```
输入：
```shell
[source.crates-io]
registry = "https://github.com/rust-lang/crates.io-index"
# 指定镜像
replace-with = 'ustc' #镜像源名 如：tuna、sjtu、ustc，或者 rustcc

# 注：以下源配置一个即可，无需全部

# 中国科学技术大学
[source.ustc]
registry = "git://mirrors.ustc.edu.cn/crates.io-index"

# 上海交通大学
[source.sjtu]
registry = "https://mirrors.sjtug.sjtu.edu.cn/git/crates.io-index"

# 清华大学
[source.tuna]
registry = "https://mirrors.tuna.tsinghua.edu.cn/git/crates.io-index.git"

# rustcc社区
[source.rustcc]
registry = "https://code.aliyun.com/rustcc/crates.io-index.git"
```