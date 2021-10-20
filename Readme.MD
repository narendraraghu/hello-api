

docker build -t hello-api .

docker run -p 3050:3000 hello-api

docker login --username=narendrakareli

docker images

docker tag d94698199328 narendrakareli/hello-api

docker push narendrakareli/hello-api

kubectl apply -f pod.yaml

kubectl apply -f nodeport.yaml

kubectl get all
