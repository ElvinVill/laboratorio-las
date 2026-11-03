# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** Elvin Arquímides Villatoro Martínez
- **Carné:** N/A
- **Correo institucional:** N/A
- **Asignatura:** Lenguajes de Programación con Aspectos de Seguridad
- **Fecha:** 02/11/2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
repositorio/
├── proyecto/
│   ├── app.py
│   ├── requirements.txt
│   └── otros archivos
└── README.md
```

## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone URL_DEL_REPOSITORIO
```

**Paso 2.** Ingresar al proyecto.

```bash
cd repositorio/proyecto
```

**Paso 3.** Instalar las dependencias.

```bash
pip install -r requirements.txt
```

**Paso 4.** Crear la Base de Datos.

```bash
python crearDB.py
```

**Paso 5.** Ejecutar la aplicación.

```bash
python app.py
```

**Paso 6.** Realizar pruebas de la aplicacion.

```bash
Entrar a 127.0.0.1/5000 desde un navegador para verificar
que la aplicación esté activa

Entrar a 127.0.0.1/registro para agregar usuarios
a la base de datos

Entrar a 127.0.0.1/login para realizar pruebas
de inicio de sesión

Realizar un intento exitoso de login

Registrar 3 intentos fallidos consecutivos
de login

Revisar el archivo eventos.log 

```

**Paso 7.** Ejecutar detector.py.

```bash
python detector.py

Revisar el archivo respuesta.log
```

