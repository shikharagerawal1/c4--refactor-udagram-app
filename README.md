# c4--refactor-udagram-app
Monolith to microservices: refactor udagram app: udagram App from monolith to microservices

You need to convert the udagram App from monolith to microservices. Basically, you need to split the code for the backend into the feed and user.

Once you do that, you need then to create the docker images for each service (frontend, backend-feed, backend-user), and a reverseproxy.

After having the docker containers, you can move to Kubernetes, prepare the deployment, services, secrets and configmap files. Create a cluster in EKS and then deploy the App.