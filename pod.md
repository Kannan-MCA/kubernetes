apiVersion: v1
kind: Pod
metadata:
  name: sample-pod
  labels:
    app: sample-app
containers:
  - name: sample-app-container
    image: nginx
