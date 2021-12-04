# znLabs_MySQL_Infra_K8s


kubectl -n znlabs-mysql run -it --rm --image=mysql:8.0 --restart=Never mysql-client -- mysql -h mysql-znlabs-dev-svc -uroot -p
