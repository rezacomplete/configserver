```
./gradlew clean build
```
```
docker build . -t rezacomplete/configserver
```
```
docker push docker.io/rezacomplete/configserver
```
```
kubectl apply -f workloads.yml
```
```
kubectl apply -f services.yml
```