# charts
```
helm package ./ -d ./publish
helm repo index ./
helm show


helm repo add lexuanchinh97 https://raw.githubusercontent.com/lexuanchinh97/charts/main/
helm search repo lexuanchinh97
helm install hello lexuanchinh97/mynginx

helm uninstall hello
```
