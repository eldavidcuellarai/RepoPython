
# Sistema de Login en Flask

Este proyecto es una aplicación web sencilla hecha con Python y Flask que permite a los usuarios iniciar sesión y cerrar sesión usando una interfaz moderna y amigable.

## ¿Qué hace la app?

- Permite a los usuarios iniciar sesión con un correo y contraseña (los usuarios están definidos en el código, no en una base de datos).
- Muestra una pantalla de bienvenida personalizada al iniciar sesión.
- Permite cerrar sesión de forma segura.
- Incluye mensajes de bienvenida y error.
- Tiene un diseño visual atractivo y moderno.

## Estructura de archivos

```
RepoPython/
│
├── app.py                # Código principal de la aplicación Flask
├── requirements.txt      # Dependencias necesarias (Flask)
├── static/
│   └── style.css         # Estilos visuales de la app
├── templates/
│   ├── login.html        # Página de inicio de sesión
│   └── welcome.html      # Página de bienvenida tras iniciar sesión
├── README.md             # Este archivo
├── GITHUB_GUIDE.md       # Guía de comandos de Git y GitHub
└── Prompts.md            # (Opcional) Archivo de prompts
```

## ¿Cómo funciona?

1. **Inicio de sesión:**  
	Al abrir la app, verás un formulario donde puedes ingresar tu correo y contraseña.  
	Ejemplo de usuarios válidos:
	- admin@test.com / admin123
	- user@test.com / user123
	- demo@demo.com / demo

2. **Pantalla de bienvenida:**  
	Si los datos son correctos, verás una pantalla de bienvenida con tu nombre y la opción de cerrar sesión.

3. **Cerrar sesión:**  
	Al hacer clic en "Cerrar sesión", la app te desconecta y vuelve al formulario de login.

## ¿Cómo ejecutar la app?

1. Instala las dependencias:
	```
	pip install -r requirements.txt
	```
2. Ejecuta la aplicación:
	```
	python app.py
	```
3. Abre tu navegador en [http://localhost:5000](http://localhost:5000)

---
