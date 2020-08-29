# Curso Git & GitHub
[![Curso en YouTube](https://cdn.icon-icons.com/icons2/1488/PNG/128/5295-youtube-i_102568.png "Curso en YouTube")](https://www.youtube.com/watch?v=u49BtIIdLv4&list=PLVPhgrU5vr6MPLPmORSxD76E8yG33YY-C "Curso en YouTube")
## Comandos
### Iniciar repositorio
	git init
### Listar configuraciones locales
	git config -l
### Editar configuraciones locales
	git config -e
### Definir nombre de usuario en git globalmente
	git config --global user.name nombreDelUsuario
### Definir email de usuario en git globalmente
	git config --global user.email emailDelUsuario
### Listar configuraciones globales
	git config --global -l
### Editar configuraciones globales
	git config --global -e
### Ver estado
	git status -sb
### Ver ramas
	git branch
### Crear rama
	git brach nombreDeLaRama
### Cambiar de rama
	git checkout nombreDeLaRama
## Comandos (malas practicas)
### Trae los cambios de un commit espeficico de otra rama
	git cherry-pick hashDeLaRama
  
