# Simulación de un Banco - CITIBANACHEEMS

## Descripción
Proyecto desarrollado para la asignatura *Modelado y Programación* (2022-2). El objetivo fue simular las operaciones básicas de un banco digital con soporte multilingüe y funcionalidades clave, implementando principios de diseño de software.

## Funcionalidades
- *Soporte multilingüe*: Menú en español, inglés y francés.
- *Opciones de usuario*:
  - Registro de nuevos usuarios.
  - Inicio de sesión seguro.
  - Consulta de saldo.
  - Transferencias bancarias entre usuarios.
  - Retiros sin tarjeta.
  - Consulta de estados de cuenta.
- *Gestión de datos*: Uso de archivos .txt para almacenar información de usuarios, saldos y movimientos.

## Tecnologías y herramientas utilizadas
- *Lenguaje de programación*: Java.
- *Gestión de dependencias y ejecución*: Apache Ant.
- *Patrones de diseño implementados*:
  - *Strategy*: Selección de idiomas y optimización de inicio de sesión.
  - *Proxy*: Control de acceso seguro.
  - *Singleton*: Gestión única de instancias de usuarios.
  - *Template*: Registro de usuarios eficiente.
  - *MVC (Modelo-Vista-Controlador)*: Organización modular del sistema.

## Ejecución
1. Asegúrate de tener configurado Java y Apache Ant.
2. Ejecuta los siguientes comandos desde la terminal:
   ```bash
   ant jar
   ant run