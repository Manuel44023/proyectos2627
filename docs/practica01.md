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

## 3. INSTALACIÓN DE HERD Y PHP 8.4

Se instala Herd como entorno de desarrollo local y se selecciona la versión **PHP 8.4**.

La versión de PHP también se puede comprobar desde la terminal:

```bash
php -v
```

**Captura:**

## 4. CLONACIÓN DEL REPOSITORIO `misitio`

Se clona el repositorio `misitio` desde GitHub para disponer de una copia local del proyecto.

```bash
gh repo clone USUARIO/misitio
```

Después accedemos a la carpeta:

```bash
cd misitio
```

**Captura:**

## 5. CONFIGURACIÓN DE HERD

Se enlaza la carpeta del proyecto `misitio` con Herd para que pueda ejecutarse como sitio web local.

Una vez configurado, Herd se encarga de servir el proyecto desde su dominio local.

**Captura:**


