Coses que he fet per publicar-ho aL GITHUB PAGES:

1. Crear un PAT (Personal Access Token) als Settings del meu compte d'usuari en permisos totals repo.
2. Al repo copiar el token a una variable del github actions anomenada GH_TOKEN (Settings -> Secrets and variables -> Actions -> New repository secret).
3. Modificar el pom.xml
4. Afegir el fitxer deploy.yml al .github/workflows/.

Ara cada vegada que faig un push s'actualitza el repo del github i si he fet les accions del maven en local per refrescar 
el javadoc, també apareix al github pages.

Se pot accedir al javadoc remotament a l'adreça:

https://iesebre.github.io/DirectAccessFile/docs/

I al landing page:

https://iesebre.github.io/DirectAccessFile/