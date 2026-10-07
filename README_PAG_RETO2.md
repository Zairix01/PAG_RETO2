# PAG_RETO2

## Datos académicos

**Universidad:** Universidad Virtual del Estado de Guanajuato (UVEG)  
**Materia:** Despliegue de aplicaciones web y móviles V2  
**Reto:** Reto 2  
**Nombre:** Zaira Gómez Martínez  
**Matrícula:** 24003579  

## ¿Qué es este repositorio?

Este repositorio contiene el proyecto desarrollado para el Reto 2 de la materia **Despliegue de aplicaciones web y móviles V2**.

El propósito del repositorio es almacenar, documentar y mantener el control de versiones de una aplicación web que fue preparada, optimizada, empaquetada y configurada para su posterior despliegue mediante un servidor web Apache.

El archivo `README.md` documenta el proceso realizado durante la preparación del proyecto, incluyendo la organización de archivos, optimización de recursos, empaquetado, versionamiento mediante GitHub y configuración del servidor web.

## Descripción del proyecto

El proyecto consiste en una página web informativa inspirada en la serie *Friends*. El sitio presenta contenido visual e información relacionada con los personajes principales.

La página fue desarrollada utilizando HTML y CSS. Debido a que su contenido es principalmente informativo, no fue necesario implementar JavaScript.

## Estructura del proyecto

```text
PAG_RETO2/
├── index.html
├── README.md
├── css/
│   └── style.min.css
└── img/
    ├── Chandler.jpg
    ├── clasificacion.jpg
    ├── Joey.jpg
    ├── monica.jpg
    ├── Phoebe.jpg
    ├── portada.jpg
    ├── Rachel.jpg
    └── Ross.jpg
```

## Proceso realizado

### 1. Preparación de la aplicación web

Se revisó la estructura inicial del proyecto y se organizaron los archivos en carpetas específicas.

La hoja de estilos fue almacenada dentro de la carpeta `css`, mientras que las imágenes utilizadas por la página fueron agrupadas dentro de la carpeta `img`.

Posteriormente, se actualizaron las rutas correspondientes dentro del archivo `index.html` para asegurar que todos los recursos continuaran cargando correctamente.

### 2. Optimización de recursos

Se realizó la optimización de los recursos utilizados por la aplicación.

La hoja de estilos CSS fue minificada y se generó el archivo:

```text
style.min.css
```

También se redujo el peso de las imágenes utilizadas en la página con el objetivo de disminuir el tamaño total del proyecto y mejorar la carga de los recursos.

Después de realizar estos cambios, se verificó que la página conservara su diseño y funcionamiento.

### 3. Empaquetado

Una vez organizada y optimizada la aplicación, se generó un archivo comprimido en formato ZIP.

El empaquetado permite conservar la estructura final del proyecto y facilita su transferencia y posterior despliegue en un servidor web.

### 4. Versionamiento

Para gestionar las versiones del proyecto se utilizó GitHub.

Se creó un repositorio llamado:

```text
PAG_RETO2
```

En este repositorio se almacenó la versión optimizada de la aplicación y se documentó el proceso mediante este archivo `README.md`.

También se utilizaron commits descriptivos para identificar los cambios realizados durante el desarrollo.

Ejemplos:

```text
feat: agrega estructura inicial del proyecto
style: organiza y minifica la hoja de estilos
perf: optimiza las imágenes del sitio
docs: agrega documentación del proyecto
```

### 5. Configuración del servidor web

Para realizar el despliegue local se seleccionó **Apache**, utilizando XAMPP como entorno de servidor.

La configuración contempla el uso de un Virtual Host, el puerto 80 y el mapeo del directorio donde se encuentra almacenado el proyecto.

El sitio será configurado para acceder mediante una dirección local simulada como:

```text
http://paginalia.local
```

## Tecnologías utilizadas

- HTML5
- CSS3
- Apache
- XAMPP
- Git
- GitHub

## Objetivo

El objetivo de este proyecto es aplicar de manera práctica los conocimientos relacionados con la preparación, optimización, empaquetado, versionamiento y despliegue de una aplicación web.
