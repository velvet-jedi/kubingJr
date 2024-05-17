# kubingJr
[link to the blogpost](https://link.medium.com/NvjMTxtHFJb)

command to create a new resource based from a YAML file
```
kubectl create -f deployment.yml
```

command to view pods
```
kubectl get pods
```

command to view deployments
```
kubectl get deployments
```

### Using kubectl to start a proxy server
This command starts a proxy to the Kubernetes API server:
```
kubectl proxy --port=8080
```

### Using kubectl to start a proxy server
This command to get the IP of kubernetes cluster:
```
minikube ip
```

### to build the image of our app locally
```
sudo docker build -t <image_name> <path_to_Dockerfile>
```

### to run the app locally
```
sudo docker build -t <image_name> <path_to_Dockerfile>
```

### to push our image to dockerhub
```
sudo docker push <image_name>
```

(find the image here)[https://hub.docker.com/r/velvetjedi/nodeapp]
