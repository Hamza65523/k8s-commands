# k8s-commands 





| Command | Description |
| ------- | ----------- |
| kubectl get pods
| kubectl get nodes
| kubectl get name
| kubectl get namespaces
| kubectl get services
| kubectl get replication controllers
| kubectl get replicasets
| kubectl get deployments
| kubectl get job
| kubectl get cronjob
| kubectl get po -o wide
| kubectl get po -w
| kubectl get po -o yaml
| kubectl get po -o json
| kubectl label pod <podname> type=frontend
| kubectl get po --show-labels
| kubectl get po -L env,type --show-labels
| kubectl get po -l type=frontend --show-labels
| kubectl label pod <podname> type=frontend --overwrite
