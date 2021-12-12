# figletcreator-ingress
## Get started 
After installing `kubectl` and `minikube` locally, run:<br>
`minikube start`<br>
`minikube dashboard`<br>
`minikube addons enable ingress`<br>

`kubectl apply -f db.yaml`. Wait for the db pod to be ready<br>
`kubectl apply -f figletcreatorservice.yaml`. Wait for the figletcreatorservice pod to be ready<br>
`kubectl apply -f ingress.yaml`<br>

Don't forget to configure your `minikube host` in your local DNS server at etc/hosts, pointing it to `app.example.com`.<br>
Good figling through Kubernetes cluster !!!