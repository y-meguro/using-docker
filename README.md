# using-docker

## About this repository

- [Docker | Adrian Mouat, Sky株式会社 玉川 竜](https://amzn.to/2PZ7xAy) の演習用
- 読書メモ
  - [Docker](https://y-meguro.gitbook.io/reading-record/other/using_docker)
- 参考
  - [using-docker](https://github.com/using-docker)

## 本と違うところ

### cowsay

- Dockerfile
  - `FROM debian/eol:wheezy` に変更した
    - [sources list in wheezy should be switched to archive · Issue #65 · debuerreotype/docker-debian-artifacts](https://github.com/debuerreotype/docker-debian-artifacts/issues/65)
  - `MAINTAINER` は deprecated になったので `LABEL` を使った

### identidock

- Dockerfile
  - `FROM python:3.8` に変更した
    - 3.4 が deprecated のため
  - uWSGI のバージョンは 2.0.18 に変更した
- これだけ別レポジトリあり [y-meguro/identidock](https://github.com/y-meguro/identidock)

### identijenk

- Dockerfile
  - `FROM jenkins:2.60.3` に変更した
