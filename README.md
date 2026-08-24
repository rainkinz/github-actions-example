##### build the project

```sh
./gradlew build
```

##### build Docker image called java-app. Execute from root

```sh
docker build -t java-app .
```

##### push image to repo

```sh
docker tag java-app demo-app:java-1.0
```
