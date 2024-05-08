# kong-helm-2024
kong helm install in kubernetes using clusterIP wihtout konga

helm repo add kong https://charts.konghq.com

helm install kong kong/kong -f values.yaml -n <namespace> --version 2.38.0 
