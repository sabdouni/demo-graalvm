# Getting Started
### Compile the code
```
./mvnw clean install
```
## Using openjdk:11-jre-slim docker image
### Build image
```
docker build -f Dockefile.openjdkslim -t graalvm-hello-openjdk-slim:0.0.1 .
```
### Check Image Size
```
docker image ls graalvm-hello-openjdk-slim:0.0.1
```
### Run Image
```
time docker run graalvm-hello-openjdk-slim:0.0.1
```
##  Using Native docker image
### Build image
```
docker build -f Dockefile.native -t graalvm-hello-native:0.0.1 .
```
### Check Image Size
```
docker image ls graalvm-hello-native:0.0.1
```
### Run Image
```
time docker run graalvm-hello-native:0.0.1
```

