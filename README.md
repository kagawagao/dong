# dong

[![NPM version](https://img.shields.io/npm/v/dong.svg?style=flat-square)](https://npmjs.org/package/dong)

          ___
      ____/ /___  ____  ____
     / __  / __ \/ __ \/ __ \
    / /_/ / /_/ / / / / /_/ /
    \____/\____/_/ /_/\__, /
                     /____/

> 又一个前端工具

## 安装

```bash
$ npm install -g dong
```

## 使用

### 查看帮助

```bash
$ dong [command] －h
```

### 初始化

```bash
$ dong init [type]
```

#### Web 项目

```bash
$ dong init web
```

### Web 服务

```bash
$ dong serve
```

**参数**

```bash
-r, --root <root>  Web 服务根目录，默认 `.`
-H, --host <host>  服务域名，默认 `127.0.0.1`
-p, --port <port>  监听端口，默认 `9527`
-m, --mock <mock>  接口请求模拟数据存放目录，默认 `api`
-o, --open         服务启动后，自动在浏览器打开，默认 `false`
-d, --debug        显示 Debug 信息，默认 `false`
```

**特性**

- [x] 静态文件服务
- [x] 模拟接口请求
- [ ] 自动编译 SCSS
- [ ] 自动重启服务

### build

```bash
dong build
```

**参数**

```bash
-r, --root <root>    Web 服务根目录，默认 `.`
-s, --size <size>    MD5 串长度，默认 `8`
-v, --views <views>  视图文件，默认 Web 服务根目录下的 `*.html`
```

**特性**

- [x] JS 文件打包压缩
- [x] 资源 MD5 值生成
- [x] 资源链接添加 MD5 串
- [ ] CSS 文件生成于压缩

## TODOs

- [ ] dong test
- [ ] dong release
