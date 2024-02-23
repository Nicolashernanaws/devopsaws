Infraestructura en AWS con Terraform
Este proyecto crea una infraestructura básica en AWS utilizando Terraform. Incluye la creación de una VPC, una subnet pública, un grupo de seguridad para SSH y una instancia EC2.

Instalación y Requisitos
Instala Terraform en tu sistema. Puedes encontrar instrucciones de instalación en el sitio web oficial de Terraform.
Configura tus credenciales de AWS. Puedes hacerlo configurando variables de entorno o utilizando un archivo ~/.aws/credentials.
Uso
Clona este repositorio en tu máquina local.
Navega al directorio del proyecto.
Ejecuta terraform init para inicializar el proyecto.
Ejecuta terraform plan para ver los cambios que se aplicarán.
Ejecuta terraform apply para aplicar los cambios y crear la infraestructura en AWS.
Consideraciones de Seguridad
Asegúrate de restringir el acceso SSH a direcciones IP específicas en lugar de abrirlo a todo el mundo.
No compartas tus credenciales de AWS públicamente.
Contribución
¡Contribuciones son bienvenidas! Si encuentras algún error o tienes alguna mejora, siéntete libre de abrir un problema o enviar una solicitud de extracción.