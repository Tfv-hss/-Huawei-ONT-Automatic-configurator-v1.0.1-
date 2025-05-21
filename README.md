# -Huawei-ONT-Automatic-configurator-v1.0.1-
Este es un proyecto que nos permite meter automaticamente un archivo de configuracion en ONTs de Huawei optixstar / This is a project that allows us to automatically insert a configuration file into Huawei Optixstar ONTs.

#Sobre el proyecto/About the project

- Este programa esta escrito en Python, nos ayuda a configurar automaticamente routers/ONTs cuando tenemos que hacer muchos, necesitamos algunos requisitos

- This program is written in Python, it helps us to automatically configure routers/ONTs when we have to do many, we need some requirements



##Requisitos

1. Carpeta con los archivos de configuración bien ubicada
1.  Folder with configuration files well located


2. En el codigo cambiar la ruta relativa con los nombres que tengan nuestros archivos
2. In the code, change the relative path with the names of our files.

------------



```html
base_dir = os.path.dirname(os.path.abspath(__file__))
xml_path = os.path.join(base_dir, "NOMBRE_DE_CARPETA", "SUB_CARPETA",   				"ARCHIVO_CONFIG.xml")
```

------------
```html
base_dir = os.path.dirname(os.path.abspath(__file__))
xml_path = os.path.join(base_dir, "FOLDER_NAME", "SUB_FOLDER",   							"CONFIG_FILE.xml")
```

------------


C:.
├───configs
│   ├───Nombre_Del_Archivo
 ..........├───Archivo.XML

------------
C:
├───configs
│ ├───File_Name
..........├───File.XML
