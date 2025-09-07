
<!-- ----------------------------------------------------------------------- -->

<br>

<div align='center'>

``` ocaml
DESARROLLO DE API Y APLICACION WEB
```

</div>

<!-- ----------------------------------------------------------------------- -->

<h1 align='center'>
    <a href='https://github.com/lord-of-castamere/Irithyll'>
        <img src='./statics/images/Siegward.webp' width='25%'
            alt='¿Quién soy yo para juzgar caminos ajenos? Si yo mismo camino como un hombre imperfecto.' />
    </a>
</h1>

<!-- ----------------------------------------------------------------------- -->

<br>

<div align='center'>
    <img src='https://img.shields.io/badge/Framework-DJANGO-blue?style=for-the-badge' alt='Framework' />
    <img src='https://img.shields.io/badge/Estado-En%20desarrollo-important?style=for-the-badge' alt='Estado actual' />
    <img src='https://img.shields.io/badge/Team-Artemis-critical?style=for-the-badge' alt='Equipo desarrollador' />
</div>


<!-- ----------------------------------------------------------------------- -->

<br>

## <samp>CONFIGURACIÓN</samp>

> **Nota:** Los siguientes pasos detallan la configuración e inicialización del proyecto desde Windows.

<br>

<!-- ----------------------------------------------------------------------- -->

#### ACTIVA EL ENTORNO VIRTUAL
``` bash
# Tras haber clonado el repositorio, crea y aciva el entorno virtual.

python -m venv venv
venv\Scripts\Activate
```

<!-- ----------------------------------------------------------------------- -->

#### INSTALA LAS DEPENDENCIAS
``` bash
# Una vez activado el entorno, instala todas las dependencias necesarias.

pip install -r Requirements.txt
```

<!-- ----------------------------------------------------------------------- -->

#### MIGRACIONES Y BASE DE DATOS
``` bash
# Aplica las migraciones para crear las tablas en la base de datos.

python manage.py makemigrations
python manage.py migrate

# NOTA: De estar realizando este proceso por primera vez, recomiendo la creación de un superusuario.
python manage.py createsuperuser
```

<!-- ----------------------------------------------------------------------- -->

#### INICIA EL SERVIDOR
``` bash
# Finalmente, inicia el servidor de desarrollo. :)

python manage.py runserver
```

<!-- ----------------------------------------------------------------------- -->

<br>

## <samp>ESTRUCTURA</samp>

> **Nota:** Estructura detallada de la organización de carpetas del proyecto.

``` bash
Backend ''' Desarrollo de API y aplicación WEB '''
├── apps
│   ├── API # API del sistema.
│   ├── Core # Secciones de acceso público.
│   └── Dashboard # Panel de administración.
│
├── media
│   └── ... # Archivos subidos por los usuarios.
│
├── statics
│   ├── css
│   │   ├── core
│   │   └── dashboard
│   ├── fonts
│   │   └── ...
│   ├── images
│   │   └── ...
│   └── scripts
│       ├── core
│       └── dashboard
│
├── templates
│   ├── core
│   └── dashboard
│
├── Artemis
│   ├── settings.py # Configuración general del proyecto.
│   ├── urls.py # URLs generales de las aplicaciones.
│   └── ...
│
├── manage.py
├── Readme.md
└── Requirements.txt
```

<!-- ----------------------------------------------------------------------- -->

<br>

#### ***- Let the sun shine upon this Lord of Cinder!***

<!-- ----------------------------------------------------------------------- -->