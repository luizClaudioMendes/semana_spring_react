# Semana spring react - devsuperior

## instalação windows
### java jdk 11
instalação do java jdk zulu
https://www.azul.com/downloads/zulu-community/

baixar o arquivo zip da versao 11 e descompactar na pasta pretendida.

configurar as variaveis de ambiente
na barra de pesquisa do windows, digitar var e abrir as variaveis do sistema.
clicar na aba avançado, variaveis de sistema
clicar em novo e dar o nome da variavel
JAVA_HOME
o valor da variavel é o local onde foi descompactado o zip
c:\programFiles......

localizar a variavel path e editar
clicar em novo e copiar e colar a localizacao onde esta o zip mais \bin

e pronto.

no cmd, digitar java -version e deve aparecer a versao do java.

### STS 
em spring.io baixar o sts
extrair os arquivos 
abrir o arquivo contents.zip e descompactar
executar o sts

### Postman
digitar no navegador getpostman
fazer o download do postman

basta executar o programa.

### Postgresql e pgAdmin
#### instalar o servidor do postgresql
no google, digitar postgresql download windows
abrir https://www.postgresql.org/download/windows/

clicar no botao de download installer

neste exemplo vamos usar a versao 12

executar o arquivo de instalaçao
instalar:
postgresql server
pgAdmin 4
stack builder
command line tools

criar uma senha padrao para o superusuario da maquina local
1234567

porta 5432

para ver se o servidor postgres esta rodando (ele roda como um serviço do windows)
na pesquisa do windows digitar serviços

na lista devera estar postgressql e devera estar em execuçao.

testar o pgAdmin
na pesquisa do windows digitar pgAdmin e o programa devera aparecer
colocar a senha de superusuario
1234567


