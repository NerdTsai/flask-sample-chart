# Dependancies
* Kubernetes
* Kubernetes cluster (eg. minikube)
* Helm

# Steps
```
git clone https://github.com/nerdtsai/flask-sample-chart.git

helm init

helm install flask-sample-chart --name=test

helm status test
```
* go to "testhost" in browser
# Note
* To enable ingress with minikube
```
minikube addons enable ingress
```
