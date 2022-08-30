# Tiltfile
#grafana
load('ext://helm_resource', 'helm_resource', 'helm_repo')
helm_repo('grafana', 'https://grafana.github.io/helm-charts')
helm_resource('mysql', 'grafana/loki-stack')

#prometheus
load('ext://helm_resource', 'helm_resource', 'helm_repo')
helm_repo('prometheus', 'https://charts.kube-ops.io')
helm_resource('nginx', 'ingress-nginx/ingress-nginx')


