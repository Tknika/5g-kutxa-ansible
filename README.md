# 5G-Kutxa Ansible

Repositorio para automatizar la instalación de todo el software de 5G-Kutxa

## Uso

Antes de ejecutar el contenido del repositorio, es necesario asegurarse de que Ansible se encuentra disponible en el ordenador. Para ello, podemos ejecutar el siguiente comando:

```
sudo apt install ansible
```

A continuación, emplearemos este comando para instalar el software:

```
sudo ansible-pull -U https://github.com/Tknika/5g-kutxa-ansible.git -i localhost,
```