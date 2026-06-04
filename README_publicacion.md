# Publicación del informe TSP

Esta carpeta contiene una versión lista para publicar del informe Quarto en HTML.

Archivo principal:

```text
index.html
```

## Opción recomendada: GitHub Pages

1. Entrar a https://github.com/new
2. Crear un repositorio nuevo, por ejemplo:

```text
informe-tsp-computacion-evolutiva
```

3. Entrar al repositorio recién creado.
4. Presionar `Add file > Upload files`.
5. Subir todo el contenido de esta carpeta `public_informe`, no la carpeta completa como carpeta anidada.
6. Confirmar con `Commit changes`.
7. Ir a `Settings > Pages`.
8. En `Build and deployment`, seleccionar:

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

9. Guardar.
10. Esperar unos minutos. GitHub entregará un link público del tipo:

```text
https://usuario.github.io/repositorio/
```

## Verificación

El archivo `index.html` debe quedar en la raíz del repositorio. Si queda dentro de una carpeta llamada `public_informe`, GitHub Pages no abrirá el informe directamente.

Este directorio incluye `.nojekyll` para que GitHub Pages publique los archivos estáticos sin procesarlos.
