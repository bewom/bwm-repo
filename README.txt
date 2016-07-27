#Versión del instalador

https://api.github.com/repos/bewom/repository/releases -> [0] -> tag_name

#Instalador

https://api.github.com/repos/bewom/repository/commits -> [0] -> commit -> tree -> url -> (open) -> tree -> files -> url
AND REPEAT <->

0- Comprobar que existe el archivo launcher_profiles.json en Roamidng/.minecraft/ THROW ERROR
1- Añadir perfil al launcher_profiles.json
2- Guardar dentro del directorio bewom, directorios y replicarlos en local en Roaming/.minecraft/bewom/
3- Recursivo en files/bewom/... hasta encontrar "blob"
4- Descargar blob con -> https://github.com/bewom/repository/raw/master/files/bewom/...
5- Fin

https://github.com/bewom/repository