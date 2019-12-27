# using-docker

## About this repository

- [Docker | Adrian Mouat, Sky株式会社 玉川 竜](https://amzn.to/2PZ7xAy) の演習用
- 読書メモ
  - [Docker](https://y-meguro.gitbook.io/reading-record/other/using_docker)
- 参考
  - [using-docker](https://github.com/using-docker)

## 本と違うところ

- Dockerfile
  - `FROM debian/eol:wheezy` に変更した
    - [sources list in wheezy should be switched to archive · Issue #65 · debuerreotype/docker-debian-artifacts](https://github.com/debuerreotype/docker-debian-artifacts/issues/65)
  - `MAINTAINER` は deprecated になったので `LABEL` を使った
