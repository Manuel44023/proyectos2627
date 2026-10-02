# PRÁCTICA 01 - CONFIGURACIÓN E INSTALACIÓN DEL ENTORNO

## 1. INSTALACIÓN Y CONFIGURACIÓN DE GIT

Se instala Git en el equipo y se configura el nombre de usuario y el correo electrónico asociados a la cuenta.

Para comprobar la instalación:

```bash
git --version
```

Para consultar la configuración:

```bash
git config --list
```

**Captura:**

![git instalado](/img/image.png)

## 2. INSTALACIÓN Y CONFIGURACIÓN DE GITHUB CLI

Se instala GitHub CLI para poder trabajar con los repositorios de GitHub desde la terminal.

Para iniciar sesión:

```bash
gh auth login
```

Una vez realizado el proceso de autenticación, comprobamos que la cuenta está correctamente configurada:

```bash
gh auth status
```

**Captura:**

![github Cli instalado](/img/image-1.png)

## 3. INSTALACIÓN DE HERD Y PHP 8.4

Se instala Herd como entorno de desarrollo local y se selecciona la versión **PHP 8.4**.

La versión de PHP también se puede comprobar desde la terminal:

```bash
php -v
```
**Captura:**

![PHP instalado](/img/image-2.png)

## 4. CLONACIÓN DEL REPOSITORIO `misitio`

Se clona el repositorio `misitio` desde GitHub utilizando **Visual Studio Code**.

En Visual Studio Code:

1. Abrimos el menú **Control de código fuente**.
2. Seleccionamos **Clonar repositorio**.
3. Introducimos la URL del repositorio de GitHub.
4. Elegimos la carpeta donde queremos guardar el proyecto.
5. Abrimos el proyecto clonado en Visual Studio Code.

Una vez clonado, comprobamos que tenemos los archivos del proyecto en el explorador de Visual Studio Code.

## 5. CONFIGURACIÓN DE HERD

Se enlaza la carpeta del proyecto `misitio` con Herd para que pueda ejecutarse como sitio web local.

Una vez configurado, Herd se encarga de servir el proyecto desde su dominio local.

**Captura:**

![HERD](/img/image-3.png)

## 6. ACCESO MEDIANTE HTTPS

Finalmente, comprobamos que el sitio funciona correctamente mediante HTTPS.

Se accede desde el navegador a la dirección local proporcionada por Herd:

```text
https://[dominio-local-de-misitio]
```

**Captura:**

![HTTPS](/img/image-4.png)

## 7. ELEMENTOS Y PLUGINS DE READ THE DOCS

Para crear esta documentación se han utilizado diferentes elementos de Markdown y las extensiones configuradas en `properdocs.yml`.

La documentación se puede previsualizar localmente mediante:

```bash
properdocs serve
```

Y se accede desde el navegador mediante:

```text
http://127.0.0.1:8000/
```
