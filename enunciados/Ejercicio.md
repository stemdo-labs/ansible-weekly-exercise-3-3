# Creación de un archivo de inventario de Ansible

Crea un archivo de inventario de Ansible que enumere al menos 2 servidores Linux. Los
servidores pueden estar en diferentes grupos según su función.

# Diseño y creación de un rol de Ansible llamado "user_management"

Diseña y crea un rol de Ansible llamado "user_management" que se encargará de la gestión de
cuentas de usuario en los servidores. Este rol debe ser reutilizable y configurable mediante
variables.

Define variables en tu rol para configurar los nombres de usuario, contraseñas y grupos de
usuarios. Utiliza variables para personalizar la creación de cuentas de usuario en función del
servidor y su función.

# Creación de un playbook principal

Crea un playbook principal que utilice el rol "user_management" para configurar cuentas de
usuario en todos los servidores de manera simultánea. El playbook debe iterar sobre los
servidores en el inventario.

Utiliza bucles en Ansible (por ejemplo, el módulo loop) para recorrer la lista de usuarios y aplicar
la configuración en todos los servidores.

Asegúrate de que las contraseñas de usuario se almacenen de forma segura utilizando Ansible
Vault o métodos equivalentes.

# Documentación detallada

Proporciona documentación detallada que explique cómo usar tu solución, incluyendo cómo
configurar las variables y cómo ejecutar el playbook.
