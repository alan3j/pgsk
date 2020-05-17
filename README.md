# pgsk
# PluralSight Getting Started with Kubernets

## Note on GKE: firewall-rule necessary to access the NodePort
`gcloud compute firewall-rules create hello-nodeport --allow tcp:30001`
