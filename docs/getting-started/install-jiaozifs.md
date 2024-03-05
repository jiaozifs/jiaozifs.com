---
sidebar_position: 1 
---

# Install JiaoziFS

> To build JiaoziFS using the source code, if you prefer not to build it on your own server, you can utilize the [JiaoziFS public platform](https://cloud.jiaozifs.com/).

### [JiaoziFS](https://github.com/jiaozifs/jiaozifs) Basic Build And Usage

#### Requirement

1. To build JiaoziFS, you need a working installation of [Go 1.22.0 or higher](https://golang.org/dl/)
2. JiaoziFS use postgres to store running data, you can install at [postgres install installation guide](https://www.postgresql.org/docs/current/installation.html)

#### Build And Running

1. clone and build

```shell
git clone https://github.com/jiaozifs/jiaozifs.git
cd jiaozifs
make build
```

After following the above steps, you should be able to see an executable file named "jzfs."

2. init program and running

```shell
./jzfs init  --db postgres://<username>:<password>@localhost:5432/jiaozifs?sslmode=disable
./jzfs daemon
```

#### run with docker

```shell
docker run -v <data>:/app -p 34913:34913 gitdatateam/jzfs:latest  --db "postgres://<user>:<password>@192.168.1.16:5432/jiaozifs?sslmode=disable" --bs_path /app/data --listen http://0.0.0.0:34913 --config /app/config.toml
```



### [JiaoziFS-ui](https://github.com/jiaozifs/jiaozifs-ui) Basic Build And Usage

#### Requirement

This configuration requires Node.js version 16.16.0.

#### Build And Running

1. clone and install

```
git clone git@github.com:jiaozifs/jiaozifs-ui.git
npm install
```

2. running

```
npm run dev
```

#### Run with docker

```
docker run -it -p 12345:80 -e JIAOZIFS_API_URL=http://api.jiaozifs.com/api/v1 gitdatateam/jiaozifs-ui:latest
```

