# git-flow-sample


### Comandos GitFlow


##### Inicialização

`git flow init`

##### Começar uma nova funcionalidade

`git flow feature start nomeFeature`

###### 1.  Cria uma feature branch local baseada na develop
###### 2.  Muda para feature branch criada

##### Finalizar uma funcionalidade 

`git flow feature finish nomeFeature`

###### 1.  Mescla feature branch na Develop
###### 2.  Remove feature branch
###### 3.  Volta para a Develop

##### Publicar funcionalidade

`git flow feature publish nomeFeature`

###### 1.  Cria feature branch remota
###### 2.  Sincroniza local com remota
###### 3.  Vai para branch criada

##### Obter funcionalidade publicada

`git flow feature pull nomeFeature`



