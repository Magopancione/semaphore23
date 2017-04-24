# semaphore23
install semaphore

File di host

L'accesso è in ssh nessuna chiave ssh

  Definre l'utente
  ansible_ssh_user=root 

  La password per l'accesso in ssh
  ansible_ssh_pass=semaphore 

  La password di root per l'utente mysql
  mysql_root_password=semaphore

Esempio di inventory



[semaphore]
192.168.1.1 ansible_connection=ssh ansible_ssh_user=root ansible_ssh_pass=semaphore mysql_root_password=semaphore
