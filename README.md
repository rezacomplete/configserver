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
kubectl apply -f pods.yml
```
```
kubectl -it exec configserver sh
```
```
kubectl get all
```
```
kubectl get ns
```
