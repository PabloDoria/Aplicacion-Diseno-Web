# Actividad 1 - Diseño de aplicaciones web

**Nombre:** Pablo Torres Doria  
**Matricula:** Pablo Torres Doria  
**Semestre:** 6  
**Carrera:** Ingeniería en desarrollo de software  
**Profesor:** Cristopher Gerardo Gaytán Díaz

## Sección de Markdown

Markdown es una sintaxis ligera y fácil de usar para formatear texto de manera que sea fácil de leer y escribir. Aquí te presento algunos de los principales elementos de formato en Markdown:
Encabezados

# Encabezado 1 
## Encabezado 2 
### Encabezado 3 
#### Encabezado 4 
##### Encabezado 5 
###### Encabezado 6 

**Texto en Negrita y Cursiva**

**Texto en Negrita** 
__Otra forma de escribir Negrita__ 
*Texto en Cursiva*
_Otra forma de escribir Cursiva_ 
**Texto en _Negrita y Cursiva_** 

**Listas**

Listas Ordenadas

1. Primer elemento 
2. Segundo elemento 
1. Subelemento 
2. Otro subelemento 
3. Tercer elemento 

Listas No Ordenadas

- Elemento 1 
- Elemento 2 
- Subelemento 
- Otro subelemento 
- Elemento 3 

**Enlaces e Imágenes**

Enlaces

[Texto del Enlace](URL) 

Imágenes

![Texto Alternativo](URL de la Imagen) 

Citas

> Esto es una cita. 

Líneas Horizontales

--- 

**Código**

Código en línea

`Código en línea` 

Bloques de Código

```markdown 
| Encabezado 1 | Encabezado 2 | 
| ------------ | ------------ | 
| Celda 1,1 | Celda 1,2 | 
| Celda 2,1 | Celda 2,2 | 

## Sección de Git.

**1. Verificar el estado de un repositorio local.**

```bash
git status

**2. Agregar archivos individuales o globalmente.**

git add <nombre del archivo o directorio>

**O para agregar todos los cambios:**

git add .

**3. Agregar comentarios a la confirmación.**

git commit -m "Mensaje descriptivo del cambio"

**4. Cargar sus cambios en el repositorio remoto.**

git push origin <nombre de la rama>

**5. Crear, explorar y eliminar ramas.**

Crear una nueva rama:

git branch <nombre de la nueva rama>

Cambiar a una rama existente:

git checkout <nombre de la rama>

Eliminar una rama:

git branch -d <nombre de la rama>

**6. Revertir un repositorio a una confirmación específica.**

git reset --hard <hash de la confirmación>
