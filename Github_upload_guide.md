# Github_upload_guide.md

## Pasos:

1. Encontrarse en la rama "Develop"
2. Crear una rama para agregar la nueva funcionalidad con el siguiente comando  
`$ git flow feature start [nombre_rama]`    
Formato nombre de la rama:
    - nombre.apellido_[descripción]
    - La descripcion debe estar en inglés
    - Verbo (add/modify) + detalles
    - Ex: **juan.perez_add_chapter_1.2.2.2**  

    (Opcional) Si se desea publicar la rama en el github:  
`$ git push --set-upstream origin [nombre_rama]`  
3. Desarrollar lo planteado
4. Una vez realizada la actividad, hacer el commit:  
`$ git add file1, file2, ...`  
`$ git commit -m [nombre_commit]`  
Formato nombre del commit:
    - feat: [descripcion]
    - La descripción debe estar en inglés
    - El verbo debe estar al final y en pasado
    - Ex: **feat: chapter 1.2.2.2. added**

5. Cerrar rama:  
`$ git flow feature finish [nombre_rama]`
6. Subirlo al github en la rama develop  
`$ git push origin` 

