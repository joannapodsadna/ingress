# ingress
Simple yaml's using ingress controller - using minikube 

Tutorial for this: https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/

Additional, two exe files to start minikube.

For ingress-test.yaml is creating only ingress service, because for deployment is using image from (--image=gcr.io/google-samples/hello-app:1.0). More infos:https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/ 

By ingress2.yaml after starting minikube and craeting deployment, it is isssue with backend ( default backend - 404). 

This problem was solved in ingress3.yaml. 

Materials:
https://medium.com/@cashisclay/kubernetes-ingress-82aa960f658e
https://hackernoon.com/setting-up-nginx-ingress-on-kubernetes-2b733d8d2f45
