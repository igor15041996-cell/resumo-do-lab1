# resumo-do-lab1
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

#1) login
az login

#2) criar resourse group 
az group create -n myResourceGroup -1 eastus

# 3) Criar Static Web App apontando para repo Github
az staticwebapp create \
 -n MystaticAppName \
 -g myresourcegroup \
 -s https://github.com/igor15041996-cell  \
 -b main \
 -l 'EastUS' \
 --app-location '/'
 
