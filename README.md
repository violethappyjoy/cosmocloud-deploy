# Task: Cosmocloud Deploy

Helm chart for deployment of '''Frontend(HTML/Vite)''', '''Backend(Fast-API)''' & '''Redis''' on Kubernetes.

## Requirements
Helm, Kubernetes, Docker, KubeCtl

## Deployment
1. Clone the repository:
  '''
    git clone https://github.com/violethappyjoy/cosmocloud-deploy.git
    cd ./cosmocloud-deploy
  '''

2. Deploy Chart:
  '''
    helm install testapp . --atomic --timeout 30s
  '''

3. Check Logs, Description & Status:
  '''
    kubectl get pods
    kubectl describe pod <pod-name>
    kubectl logs <pod-name>
  '''
