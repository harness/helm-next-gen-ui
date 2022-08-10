#Helm chart for next-gen-ui

to update/publish:

Bump version of src/Chart.yaml

helm package src -d charts

helm repo index charts
