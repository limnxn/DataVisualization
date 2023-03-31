# Analytics

## Introduction

You can clone this repository to try a data exploration and visualization platform.

## First

### If you have a dump file

```bash
$ cp yourdumpfile mysql/initdb.d
```
## Docker

### Start app containers

```bash
$ docker-compose up -d
```

- `3000` Grafana
- `3030` Metabase
- `8080` Superset

## Documents

- [Grafana Documentation](https://grafana.com/docs/grafana/latest/)
- [Metabase Documentation](https://www.metabase.com/docs/latest/)
- [What is Apache Superset?](https://superset.apache.org/docs/intro/)
