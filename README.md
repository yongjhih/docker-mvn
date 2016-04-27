# docker-mvn

## Usage

Install mvn wrapper:

```sh
docker run -it --rm -v "$PWD":/usr/src/mymaven -w /usr/src/mymaven maven mvn -N io.takari:maven:wrapper
```

Install mvn wrapper 3.3.3:

```sh
docker run -it --rm -v "$PWD":/usr/src/mymaven -w /usr/src/mymaven maven mvn -N io.takari:maven:wrapper -Dmaven=3.3.3
```

