
# Como subir una carpeta local a un repo de Github

Se asume que el repo en Github ya ha sido creado manualmente.

Nos dirigimos a la carpeta raiz en nuestra terminal:

```bash
cd <root_folder_name>
```
Ejecutamos el siguiente comando para inicializar un repositorio de github en la carpeta raiz:

```bash
git init
```

Cuando creamos el repo manualmente en Github nos debe dar un url de este tipo:

```http
https://github.com/username/project_name.git
```

Ejecutamos el siguiente comando para enlanzar el repo local con el repo de Github:

```bash
git remote add origin <URL_de_Github>
```

Ejecutamos los comandos basicos para agregar los archivos nuevos:

```bash
git add .
git commit -m 'first commit'
```

Ejecutamos el siguiente comando para renombrar la rama master (que viene por defecto) a main:

```bash
git branch -M main
```

Finalmente ejecutamos el siguiente comando para pushear los cambios al repositorio de Github:

```bash
git push -u origin main
```



