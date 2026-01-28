# Implementar la validación del Email - Capturas del programa y su ejecución con el email

# Sistema de Gestión de Personas con PySide6

Aplicación de escritorio desarrollada en Python utilizando PySide6 (Qt for Python) que implementa un sistema CRUD para la gestión de información de personas con validación de correo electrónico.

## Descripción

Este proyecto es una aplicación de interfaz gráfica que permite registrar, visualizar, editar y eliminar información de personas. La aplicación cuenta con validación en tiempo real de direcciones de correo electrónico utilizando expresiones regulares, garantizando la integridad de los datos ingresados.

## Características

- **Interfaz gráfica intuitiva**: Diseñada con Qt Designer y PySide6 para una experiencia de usuario fluida
- **Validación de email**: Implementación de validación de correo electrónico mediante regex
- **Gestión completa de datos**: Operaciones CRUD (Crear, Leer, Actualizar, Eliminar)
- **Feedback visual**: Mensajes de confirmación y alertas para el usuario
- **Arquitectura modular**: Separación de la lógica de negocio y la interfaz gráfica

## Tecnologías Utilizadas

- **Python 3.x**
- **PySide6**: Framework para desarrollo de interfaces gráficas
- **Qt Designer**: Para el diseño de la interfaz de usuario
- **Expresiones Regulares**: Para validación de formato de email

## Estructura del Proyecto

```
Pyside6/
│
├── main.py              # Punto de entrada de la aplicación
├── vtnPrincipal.py      # Ventana principal de la aplicación
├── persona.py           # Clase modelo para la entidad Persona
├── persona2.py          # Lógica de negocio y validaciones
├── interfaz.ui          # Archivo de diseño de Qt Designer
└── README.md            # Documentación del proyecto
```

## Funcionalidades Principales

### Validación de Email
La aplicación implementa una validación robusta de correos electrónicos que verifica:
- Formato correcto del email (usuario@dominio.extensión)
- Caracteres válidos en el nombre de usuario
- Dominio válido con extensión apropiada

### Gestión de Personas
- **Agregar**: Registro de nuevas personas con nombre y email validado
- **Visualizar**: Listado de todas las personas registradas
- **Editar**: Modificación de información existente
- **Eliminar**: Eliminación de registros de la base de datos

## Capturas de Pantalla
<img width="1600" height="900" alt="Captura de pantalla 2026-01-27 190954" src="https://github.com/user-attachments/assets/f7c094fd-d699-41dc-bb76-175a586a751c" />
<img width="1600" height="900" alt="Captura de pantalla 2026-01-27 191012" src="https://github.com/user-attachments/assets/ce3cda9d-e492-495d-be92-8fba52299d5c" />
<img width="1600" height="900" alt="Captura de pantalla 2026-01-27 191111" src="https://github.com/user-attachments/assets/ad8ceb70-a3ba-4a7c-b0c2-97cff1db62f6" />
<img width="1600" height="900" alt="Captura de pantalla 2026-01-27 191129" src="https://github.com/user-attachments/assets/b9344036-cad4-42af-906d-51f11883539b" />
<img width="1600" height="900" alt="Captura de pantalla 2026-01-27 191142" src="https://github.com/user-attachments/assets/f4dfac7f-32db-472f-af97-68841f59454e" />
<img width="1600" height="900" alt="Captura de pantalla 2026-01-27 191155" src="https://github.com/user-attachments/assets/42d14e24-977c-4ad7-8628-ddf478f31daa" />
<img width="1600" height="900" alt="Captura de pantalla 2026-01-27 191204" src="https://github.com/user-attachments/assets/2bba5c37-150a-4d7c-97e4-f086c68d0f76" />


## Casos de Uso

Esta aplicación es ideal para:
- Aprendizaje de desarrollo de interfaces gráficas con PySide6
- Implementación de validaciones en aplicaciones de escritorio
- Gestión simple de contactos o directorios
- Base para proyectos más complejos de gestión de información


## Autor
**Javier**
- GitHub: [@Javier2712A](https://github.com/Javier2712A)
