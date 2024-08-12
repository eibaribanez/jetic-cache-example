# jetic-cache-example

#Configmap.yaml
```
apiVersion: v1
kind: ConfigMap
metadata:
  name: user-config
  namespace: dev
data:
  email: "user@example.com"
  id: "12345"
  name: "John Doe"
```

#Secret.yaml
```
apiVersion: v1
kind: Secret
metadata:
  name: user-secret
  namespace: dev
type: Opaque
data:
  username: "dXNlcm5hbWUxMjM="
  password: "cGFzc3dvcmQxMjM="
```
