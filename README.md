# semaphore23
install semaphore

File di host

Definre l'utente
ansible_ssh_user=root 

la password per l'accesso in ssh
ansible_ssh_pass=semaphore 

la password di root per l'utente mysql
mysql_root_password=semaphore

Esempio 
[semaphore]
192.168.1.1 ansible_connection=ssh ansible_ssh_user=root ansible_ssh_pass=semaphore mysql_root_password=semaphore