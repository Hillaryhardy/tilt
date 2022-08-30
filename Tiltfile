# Tiltfile
#grafana
load('ext://helm_resource', 'helm_resource', 'helm_repo')
helm_repo('bitnami', 'https://charts.bitnami.com/bitnami')
helm_resource('grafana', 'bitnami/grafana')

#prometheus
load('ext://helm_resource', 'helm_resource', 'helm_repo')
helm_repo('bitnami', 'https://charts.bitnami.com/bitnami')
helm_resource('prometheus', 'bitnami/kube-prometheus')

