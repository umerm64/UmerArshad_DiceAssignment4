# UmerArshad_DiceAssignment4
Assignment 04 - Minikube

## Setting up minikube
In order to install minikube, refer to this link: https://minikube.sigs.k8s.io/docs/start/

### Step1
Download the binaries:
```
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube
```

### Step2
Start setting up the installation:
```
minikube start
```

## Deployin the application:
After minikube is installed, use the following command to setup the deployments and services required under this assignment #4.
```
minikube kubectl -- apply -f manifest.yml 
```

## Assignment demonstation
The output of each assignment step and how its performed is provided in the file `UmerArshadAssignment4.docx`
