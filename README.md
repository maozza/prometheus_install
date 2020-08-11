# prometheus_install
ansible playbook, download and install node_exporter or mongo exporter

## examples

### mongo exporter
``` 
ansible-playbook mongodb-exporter.yml -e"MONGO_USER=root MONGO_PASSWORD=${PASS} MONGO_PORT=27017" -i hosts
```
### node exporter
```
ansible-playbook node_exporter.yml -i hosts
```
