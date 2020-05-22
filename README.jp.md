# python3_docker

* Python3のためのDockerコンテナ

## コンテナ開始

まずこれをcloneする

```
cd python3_docker
docker-compose up -d --build
```

## コンテナにつなぐ

```
docker-compose exec python3 bash
```

### pipインストール手順

```
python -m pip install numpy
python -m pip install pandas
python -m pip install matplotlib
python -m pip install networkx
python -m pip install pyyaml
python -m pip install xlsxwriter
python -m pip install tornado
```

## ライブラリ確認

```
docker-compose exec python3 bash
python -m pip list
```

## このコンテナ消す

```
docker-compose down
```
