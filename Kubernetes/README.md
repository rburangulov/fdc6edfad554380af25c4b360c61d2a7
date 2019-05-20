hosts file example

[master]  
89.108.103.46 ansible_user='root'  
[worker]  
89.108.103.47 ansible_user='root'  
89.108.103.209 ansible_user='root'  
[all:vars]  
api_address=89.108.103.46  
master_ip=89.108.103.46  
master_hostname=89-108-103-46  
cluster_subnet=89.108.103.46/24  
