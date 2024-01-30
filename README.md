# Prometheus & Grafana

How to deploy
****

```
kubectl apply -f .
```

Navigate to http://localhost:3000 in your web browser and use the login credentials specified in the secret file 
(decrypted) to access Grafana. It is already configured with prometheus as the default datasource.
