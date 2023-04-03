pwd = 4833m4882mcm28xmfj

NDgzM200ODgybWNtMjh4bWZq

curl -LO https://k8s.io/examples/application/wordpress/mysql-deployment.yaml




curl -LO https://k8s.io/examples/application/wordpress/wordpress-deployment.yaml

kubectl apply -k ./ 
kubectl delete -k ./