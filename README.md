# 神戸大学 工学部 市民工学科 卒論用Latexテンプレート

## Usage

- Dockerの[インストール](https://docs.docker.com/get-docker)
- 以下のようにコンパイル

```console
$ docker run -v /path/to/dir/:/workdir paperist/alpine-texlive-ja platex thesis.tex
$ docker run -v /path/to/dir/:/workdir paperist/alpine-texlive-ja platex thesis.tex
$ docker run -v /path/to/dir/:/workdir paperist/alpine-texlive-ja dvipdfmx thesis.dvi
```
