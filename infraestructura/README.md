# Proyecto Terraform - Infraestructura Local

Este proyecto demuestra el uso de Terraform para crear infraestructura utilizando el concepto de Infrastructure as Code.

## Herramientas utilizadas

- Terraform
- Visual Studio Code
- Git

## Infraestructura creada

El proyecto crea automáticamente una carpeta llamada **infraestructura** con los siguientes recursos:

- servidor1.txt
- servidor2.txt
- red.txt

Estos archivos representan servidores y una red simulada.

## Pasos para ejecutar el proyecto

1. Clonar el repositorio

git clone (URL DEL REPOSITORIO)

2. Entrar a la carpeta del proyecto

cd terraform-proyecto

3. Inicializar Terraform

terraform init

4. Ver el plan de infraestructura

terraform plan

5. Crear la infraestructura

terraform apply

Luego de ejecutar estos comandos, Terraform creará la infraestructura definida en el archivo main.tf.