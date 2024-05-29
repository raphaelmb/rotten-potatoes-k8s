# Notes

## Database DSN
1. Set values on the following: ```"Host=;Database=;Username=;Password=;SSL Mode=Require;Trust Server Certificate=true"```
2. Download SSL certificate
3. Create k8s secret
4. Encode DSN in base64 for secret -- ```echo -n DSN | base64```

## Ingress Controller
1. Install nginx ingress controller via script -- find it on its github repo
2. It creates a different namespace (ingress-nginx)
3. nip.io ```app.EXTERNAL_IP.nip.io```