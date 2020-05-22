# python3_docker

* it is docker setting for Python3

## Start container

first clone the repositpry.

```
cd python3_docker
docker-compose up -d --build
```

## Connect container

```
docker-compose exec python3 bash
```

### Also install

```
python -m pip install numpy
python -m pip install pandas
python -m pip install matplotlib
python -m pip install networkx
python -m pip install pyyaml
python -m pip install xlsxwriter
python -m pip install tornado
```

## Check libraries

```
docker-compose exec python3 bash
python -m pip list
```

## Through out the container

```
docker-compose down
```
