piVersion: v1
kind: Pod
metadata:
  name: nodeport-pod
  labels:
    app: nginx
spec:
  containers:
  - name: cont1
    image: nginx
    ports:
      - containerPort: 8
