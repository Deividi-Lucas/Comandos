# Como criar comando no linux (debian)

### Instruções
* Para fazer um comando no linux temos que entender que é uma linguagem back-end.
* Os comandos são interpretados pelo __BASH__, o qual é um interpretador de comandos. Vários comandos são escrito em python, perl entre outras linguagens
* __Todos os comandos com SuperUsuário.__
#### Passo a passo
1. Acessar o diretório _/usr/bin_ (local onde está todos os comandos)

2. Criar um arquivo com permissões X, o qual serve para execução do mesmo. (touch name)
3. Atribuir ao arquivo a permissão de exercutável +x  (chmod +x)

4. Após criar o arquivo, acessar o mesmo e colocar na primeira linha a configuração abaixo:
``` comando de configuração
#!/usr/bin/python3
```
5. O arquivo já está pronto para receber alterações em python.

### Exemplo a seguir:

``` Comando para atualização
#!/usr/bin/python3

#Importando biblioteca
import os

# Verificação de atualização
os.system('sudo apt update')

# Atualização de todos os pacotes
os.system('sudo apt upgrade')
```