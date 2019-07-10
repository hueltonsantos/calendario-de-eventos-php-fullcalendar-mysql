# calendario-de-eventos-php-fullcalendar-mysql
Calendario de Eventos com suporte a usuários. (PHP, MySQL, JS, Bootstrap, FullCalendar).

<p align="center">
<img src="https://firebasestorage.googleapis.com/v0/b/naoapaga-d8a12.appspot.com/o/calendariodeeventosprint4.png?alt=media&token=4db4b762-2903-49ea-8165-5488a6c9c275" width="350" height="200" hspace="20"/><img src="https://firebasestorage.googleapis.com/v0/b/naoapaga-d8a12.appspot.com/o/calendariodeeventoprint3.png?alt=media&token=9f7bf151-1025-488d-8ad8-41fe833a3cde" width="350" height="200" />
</p>

Calendário WEB onde pode-se criar eventos e conta com uma edição customizada de arrastar e soltar através do FullCalendar ligado ao banco MySQL.

## Instalando

Vá na pasta do seu servidor (Usei o XAMPP 7.3.6) no meu caso a pasta 'htdocs' em outros servidores como Wamp é a 'www' e execute o comando git clone ou baixe os arquivos e mova até a mesma.

```
git clone https://github.com/GabrielpBiu/calendario-de-eventos-php-fullcalendar-mysql.git
```
Agora vá até seu banco de dados no meu caso localhost/phpmyadmin crie um novo banco com o nome calendário e importe o arquivo calendario.sql que contém o Banco de dados e itens pré cadastrados como os Usuários, recomendo abrir o arquivo e verificar os dados. Como as senhas estão em Sha1 deixarei a baixo sem a criptografia:

```
Usuario: Gabriel
Senha: 0987

Usuario: Carlos
Senha:1234
```
Pronto basta abrir o diretório onde se encontra os arquivos através do seu servidor, se for local: localhost/NomedaPasta.


