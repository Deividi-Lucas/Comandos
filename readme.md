# Comandos para terminal Linux, Windows e Git 
**Respositório para consulta e estudo.**
 
## Linux 
##### Navegação
* mkdir ➡️ para criar uma 'pasta/diretorio'
* rmdir ➡️ para excluir uma 'pasta/diretorio'
* rm ➡️ para excluir um arquivo
* rm -r ➡️ para excluir diretório(pasta)
* mv ➡️ para mover arquivo | e também funciona para renomear o arquivo
* cd ➡️ Utilizado para movimentação de diretório(pastas)
* man ➡️ Abre o manual do computador que pesquisar
* ls -l ➡️ para visualizar o propriedades
* ls ➡️ Para visualizar arquivo no diretorio
##### Menu do computador
* shutdown ➡️ para desligar o computador atravez do terminal
* reboot ➡️ para reinicar o computador atravez do terminal

##### Gerenciador de pacotes
* apt-get install (pacote) ➡️ para instalação de pacotes
* apt-get remove (pacote) ➡️ para remoção de pacotes
* apt-get upgrade (pacote) ➡️ para atualização de pacotes
* snap install (pacote) ➡️ para instalação de pacotes
* snap remove (pacote) ➡️ para remoção de pacotes


##### Modo Root
* passwd ➡️ para mudar a senha Root 
* sudo su ➡️ Entra no Root

##### Manipulador de arquivo
* touch ➡️ para criar um arquivo de qualquer tipo.
* chown ➡️ altera o proprietário do arquivo, muito bom para quando não necessita de usuário root ( Exemplo: sudo chown deividi [arquivo] chgrp -
altera o grupo de um arquivo
* chmod ➡️ Altera a Permissão de um arquivo, mais usado para arquivo que não são executavel ou sem leitura e gravação.
* nano ➡️ Editor de código
* vim ➡️ Editor de código
* code ➡️ (visual studio code) IDE
* Gedit ➡️ Editor de código

##### Para comando de volume pelo terminal

* amixer -D pulse sset Master 50% ➡️ Controla volume master do computador

##### Verificação na Rede
* hostname - Mostra o nome da máquina
* hostnamectl set-hostname (NOME DA MÁQUINA) - Usado para alterar o nome da máquina pelo terminal 
* Ipconfig - Mostra ip da maquina entre outras informações como: MAC, broadcast, DNS, DHCP
* Ping - teste para verificar rede e internet
* Nmap - Analisador da rede

##### Diversos 

* Para ler o comando de forma lenta colocar '| more'
* w | who | last ➡️ comando usado para ver quem acessou o ssh
* history - mostra o historico dos comandos passados 


## Windows 


##### Controle do computador
* shutdown -s -t 0 ➡️ Para desligar o computador imediatamente
* shutdown -r -t 0 ➡️ para reiinicar o computador imediatamente

##### Gerenciador de pacotes 
* winget ➡️ para instalação de pacotes
* chocolatey - choco [opção] [arquivo] ➡️ para maior duvida acesse o site ( https://chocolatey.org/ )

##### Diversos
* color ➡️ para alterar coloração das letras no terminal
* dir ➡️ para visualizar arquivos no diretório
* tree ➡️ Mostra todos arquivos em pastas e subpastas

## GIT
* git init ➡️ Para iniciar um repositório vazio( inicio de todo conteúdo novo)
* git status ➡️ Para verificação da situação dos commites e programas que foram modificados
* git add ➡️ Para adição 
* git commit ➡️ para fazer uma nova versão
* git push ➡️ para subir para o github
* git log ➡️ Mostra histórico de commit
* git show ➡️ Mostra as alterações feitas no código
* git pull ➡️ Para puxar do arquivos do github
* git clone ➡️ Clona repositório do github
