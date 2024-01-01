---
title: jiaozifs
sidebar_label: jiaozifs
slug: /
hide_table_of_contents: true
---



## 架构图



## 框架设计

轻松获得支撑千万日活服务的稳定性，内建级联超时控制、限流、自适应熔断、自适应降载等微服务治理能力，无需配置和额外代码，微服务治理中间件可无缝集成到其它现有框架使用，极简的 API 描述，一键生成各端代码，自动校验客户端请求参数合法性，大量微服务治理和并发工具包。

## 框架特点

强大的工具支持，尽可能少的代码编写，极简的接口，完全兼容 net/http，支持中间件，方便扩展，高性能，面向故障编程，弹性设计，内建服务发现、负载均衡，内建限流、熔断、降载，且自动触发，自动恢复，API 参数自动校验，超时级联控制，自动缓存控制，链路跟踪、统计报警等，高并发支撑，稳定保障了疫情期间每天的流量洪峰。

## 代码自动生成

go-zero 包含极简的 API 定义和生成工具 goctl，可以根据定义的 api 文件一键生成 Go, iOS, Android, Kotlin, Dart, TypeScript, JavaScript 代码，并可直接运行。

```bash
goctl -h
A cli tool to generate api, gRPC, model code

GitHub: https://github.com/zeromicro/go-zero
Site:   https://go-zero.dev

Usage:
  goctl [command]

Available Commands:
  api               Generate api related files
  bug               Report a bug
  completion        Generate the autocompletion script for the specified shell
  docker            Generate Dockerfile
  env               Check or edit goctl environment
  help              Help about any command
  kube              Generate kubernetes files
  migrate           Migrate from tal-tech to zeromicro
  model             Generate model code
  quickstart        quickly start a project
  rpc               Generate rpc code
  template          Template operation
  upgrade           Upgrade goctl to latest version

Flags:
  -h, --help      help for goctl
  -v, --version   version for goctl


Use "goctl [command] --help" for more information about a command.
```

## 用户列表
