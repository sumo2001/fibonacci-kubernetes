# fibonacci-kubernetes
- Considering you have proper installations for minikube and kubernetes!, No? -> refer this [minikube](https://minikube.sigs.k8s.io/docs/start/) and [kubernetes](https://kubernetes.io/docs/tasks/tools/)
- Dont know what are these?, go on read my blog -> https://sumododda.medium.com/what-and-why-is-kubernetes-bb50d1a532be
## Architecture
![image](https://user-images.githubusercontent.com/51809378/162626435-74da17b1-cd64-4234-afc5-8a83f97b4fb1.png)

## What is happening here?
- You know, fibonacci number?, we will be calucating the fibonnaci number on the index given
- ![image](https://user-images.githubusercontent.com/51809378/162627399-2abbc12a-4241-4a22-b650-4672e3ddabba.png)
- We will be using an [ingress image](https://github.com/kubernetes/ingress-nginx/) to capture input from the end user and later on, will serve them to our express server and react clients
- So the postgres will store all the values the user or server calculated before
- 
## Install
- git clone https://github.com/sumo2001/fibonacci-kubernetes.git
- cd fibonacci-kubernetes/
- minikube start
- kubectl get pods
- kubectl create secret generic pgpassword --from-literal PGPASSWORD=12345asdf
- kubectl apply -f k8s
- minikube ip
- open your browser and type in your minikube displayed ip
## 
- Step 1 
- ![image](https://user-images.githubusercontent.com/51809378/162624718-f39c531a-120a-4715-a5ca-c039b495bb1c.png)
- Step 2
- ![image](https://user-images.githubusercontent.com/51809378/162625093-6c8218db-466f-4d6f-8595-1738bdbba39f.png)
- Step 3
- ![image](https://user-images.githubusercontent.com/51809378/162625216-75bb28d5-ce14-406e-8562-6ed91a19a07e.png)
- Step 4
- ![image](https://user-images.githubusercontent.com/51809378/162625422-a2d5ed16-856c-40ec-adc9-2a0f172947ef.png)



