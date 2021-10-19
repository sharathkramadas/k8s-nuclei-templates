# K8S Nuclei Templates

Nuclei templates for K8S security scanning


```bash
nuclei -t kube-api-scan.yaml -target https://<ip>:6443
```

```bash
nuclei -t kubelet-scan.yaml -target http://<ip>:10250
```

```bash
nuclei -t etcd-scan.yaml -target http://<ip>:2379
```
