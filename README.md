#Versión del instalador

https://api.github.com/repos/bewom/repository/releases -> [0] -> tag_name

#Instalador

https://api.github.com/repos/bewom/repository/commits -> [0] -> commit -> tree -> url -> (open) -> tree -> files -> url
AND REPEAT <->

- Comprobar que existe el archivo launcher_profiles.json en Roamidng/.minecraft/ THROW ERROR
- Añadir perfil al launcher_profiles.json
- Guardar dentro del directorio bewom, directorios y replicarlos en local en Roaming/.minecraft/bewom/
- Recursivo en files/bewom/... hasta encontrar "blob"
- Descargar blob con -> https://github.com/bewom/repository/raw/master/files/bewom/...
- Fin

https://github.com/bewom/repository