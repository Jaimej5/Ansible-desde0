# Ansible-desde0

## Prueba1

Para verificar la conectividad con los hosts especificados en el archivo de inventario utilizando Ansible, ejecuta el siguiente comando. Este comando solicitará la contraseña SSH para el usuario `formacion`:

```bash
ansible -i inventario all -m ping -u formacion --ask-pass

