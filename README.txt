https://api.github.com/repos/bewom/repository/commits -> [0] -> commit -> tree -> url
https://api.github.com/repos/bewom/repository/git/trees/e27a0c714739e1a7f565e51156a8f927febf2e84 -> tree -> files -> url
AND REPEAT <->

0- Comprobar que existe el archivo launcher_profiles.json en Roamidng/.minecraft/ THROW ERROR
1- Añadir perfil al launcher_profiles.json
2- Guardar dentro del directorio bewom, directorios y replicarlos en local en Roaming/.minecraft/bewom/
3- Recursivo en files/bewom/... hasta encontrar "blob"
4- Descargar blob con -> https://github.com/bewom/repository/raw/master/files/bewom/...
5- Fin

https://github.com/bewom/repository