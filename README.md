# 1846-kubernetes


Pods
`kubectl get pods -o wide`

Services
`kubectl get svc -o wide`

ClusterIP > NodePort > LoadBalance

ClusterIP: interno, comunicação entre pods
NodePort: externo, expondo serviço/aplicação/porta
LoadBalance: cloud, utilizando sistema de balanceamento de carga do provedor (AWS, GCP, Azure..)
