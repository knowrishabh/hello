# Hello

## Prerequisites

 * JAVA 11, Maven 3.6, docker


## Developer environment


 * build artifacts

```
mvn clean install
```

* build installer

```
mvn clean install -f installer
```

* build distribution

```
mvn clean install -f dist
```

 * run distribution

```
$ docker run -d -p 8181:8181 --rm --name hello odl-hello
$ docker exec -ti hello bash
```
