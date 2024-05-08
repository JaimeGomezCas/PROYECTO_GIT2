# Tareas de GitFlow
## Nombre del Estudiante: [Arturo, Jaime, Youssef]
## Fecha de Inicio: [08/05/2024]
## Fecha de Finalización: [08/05/2024]
---
### Tarea 1: Creación del Proyecto
- [x] Clonar el repositorio del proyecto.
```
git init
git clone https://github.com/JaimeGomezCas/1-DAM.git
```
- [x] Inicializar GitFlow en el repositorio local.

```
git flow init
```

- [x] Crear y cambiar a la rama `develop`.
````
git branch develop
git checkout develop
````
### Tarea 2: Implementación de Características

#### Características: 
- [x] Crear una nueva rama de características desde `develop`.
```
git flow feature start 'nombre de la rama'
//En este caso serian las ramas de Arturo, Youssef Y Jaime
```
- [x] Hacer commits regulares mientras se trabaja en la característica.
```
git commit -m "mensaje del commit"
```


- [x] Fusionar la rama de características en `develop`.
```
git merge
```
- [x] Eliminar la rama de características.
```
git flow feature finish
```
### Tarea 3: Integración y Pruebas
- [ ] Integrar la rama `develop` en `master`.
```
git merge
//desde develop
```

### Tarea 4: Documentación y Entrega
- [ ] Crear la documentación del proyecto utilizando Markdown.
- [ ] Completar la sección de introducción, estructura del repositorio, instalación, uso, contribución, licencia,
archivos de entrega, instrucciones de entrega, plazo de entrega y contacto.
- [ ] Revisar y verificar la documentación para asegurarse de que esté completa y precisa.
- [ ] Entregar la documentación según las instrucciones del profesor o instructor.
---
## Notas Adicionales o Comentarios: [Notas o Comentarios adicionales]
