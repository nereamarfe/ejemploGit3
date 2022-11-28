# ejemploGit3
1. Creamos un repositorio nuevo en github con un README y un .gitignore
![creandoRepo](E:\IntelliJproyectos\ejemploGit3\img\01_CreandoRepositorio.PNG)
2. Creamos un proyecto nuevo marcando la opción "Create Git repository"
![creandoProyecto](E:\IntelliJproyectos\ejemploGit3\img\02_creandoProyectoConRepositorio.PNG)
3. Añadimos el repo de github como remoto e intentamos hacer un pull
![primerstatus](E:\IntelliJproyectos\ejemploGit3\img\03_primerStatus.PNG)
![conflictoPull](E:\IntelliJproyectos\ejemploGit3\img\04_conflictoConPull.PNG)
4. Quitamos los cambios del stage, deshacemos los git adds.
![quitamosAdds](E:\IntelliJproyectos\ejemploGit3\img\05_quitamosLosAdds.PNG)
5. Volvemos a intentar hacer el pull
![IntentamosPullNuevamente](E:\IntelliJproyectos\ejemploGit3\img\06_volvemosaIntentarelPull.PNG)
6. Al haber creado dos .gitignore borramos el local y nos quedamos con el remoto.
A continuación hacemos pull de nuevo.
![borramosYPULL](E:\IntelliJproyectos\ejemploGit3\img\07_borramosGitIgnoreYHacemosPull.PNG)
7. Ahora tenemos en local lo del remoto en main. Hacemos el primer commit y lo subimos al repo.
![addYPrimerCommit](E:\IntelliJproyectos\ejemploGit3\img\08_addYHacemosPrimerCommit.PNG)
8. Se ha subido bien, pero a la rama master mientras que main se mantiene en su primer commit. Tenemos que eliminar la rama main de github.
![ramaAtras](E:\IntelliJproyectos\ejemploGit3\img\09_PushAlRemotoyTraemosElOriginMasterAHead.PNG)
![ramamain](E:\IntelliJproyectos\ejemploGit3\img\10_ramaMainRemota.PNG)
![ramaMaster](E:\IntelliJproyectos\ejemploGit3\img\11_RamaMasterRemoto.PNG)
![borramosMain](E:\IntelliJproyectos\ejemploGit3\img\12_borramosRamaMain.PNG)
9. Añadimos commit de la modificación del proyecto local.
![modificoProyecto](E:\IntelliJproyectos\ejemploGit3\img\13_modificandoProyecto.PNG)
![commitModificacion](E:\IntelliJproyectos\ejemploGit3\img\14_commitModificandoProyecto.PNG)
10. Creamos rama para corregir bug.
![creamosFixBug](E:\IntelliJproyectos\ejemploGit3\img\15_creamosRamaFixBug.PNG)
11. Corregimos proyecto
![corrigiendo1](E:\IntelliJproyectos\ejemploGit3\img\16_corrigiendoBug1.PNG)
![corrigiendo2](E:\IntelliJproyectos\ejemploGit3\img\17_corrigiendoBug2.PNG)
12. Commiteamos la corrección y hacemos push.
![commitCorreccion](E:\IntelliJproyectos\ejemploGit3\img\18_commitDelFixBug.PNG)
13. Mergeamos a master la rama con el bug solucionado.
![mergeRamas](E:\IntelliJproyectos\ejemploGit3\img\19_hacemosElMerge.PNG)