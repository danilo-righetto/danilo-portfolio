# Portfólio - Danilo Righetto

Descrição: Criação de Template com base no site [Ricardo Viana Vargas](https://ricardo-vargas.com/pt/)

Status
----
Em desenvolvimento!

### Objetivo

Criar o template e posteriormente implementá-lo utilizando o CMS [WordPress](https://wordpress.org/)

### Pré requisitos do ambiente

* [PHP >= 5.6](https://secure.php.net)
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension (--enable-mbstring)
* [NodeJS](https://nodejs.org)
* [Composer](https://getcomposer.org)
* [Bower](http://bower.io)
* [gulp](http://gulpjs.com/)
* [npm](https://www.npmjs.com/)
* [phpDocumentor](https://www.phpdoc.org/)

### Rodar o web service com o servidor embutido do PHP 7.0

```sh
  $ php artisan serve

  $php -S localhost:8000 -t public

  $php -S localhost:8000 -t public public/index.php
```

### Abrir no browser

Com o servidor embutido do PHP:
[http://localhost:8000](http://localhost:8000)

### Rodar o web service no XAMPP

Instale o [XAMPP](https://www.apachefriends.org/pt_br/download.html) no seu computador.

Copie para a pasta "C:\xampp\htdocs" o projeto [html-css-definitivo]()

Após a instalação acesse o diretório "C:\xampp\apache\conf\extra" e edite o arquivo: [httpd-vhosts.conf]()

No final do arquivo acrescente esse trecho abaixo:

```sh
<VirtualHost ramais.dev:80>
  DocumentRoot "C:\xampp\htdocs\danilo-portfolio"
  ServerAdmin danilo-portfolio.dev
  <Directory "C:\xampp\htdocs\danilo-portfolio">
        Options Indexes FollowSymLinks
        AllowOverride All
        Require all granted
  </Directory>
</VirtualHost>
```

Acesse o diretório "C:\Windows\System32\drivers\etc" e edite o arquivo: [hosts]()

No arquivo "hosts" acrescente a seguinte linha e em seguida salve:

```sh
  127.0.0.1 danilo-portfolio.dev
```

Após isso reinicie o Apache do XAMPP e no seu navegador acesse: http://html-css-definitivo.dev

## Documentação

Acesse a pasta `Documents` para mais informações sobre o projeto.

## Autor

#### [Danilo Righetto](https://danilo-righetto.github.io/) - Analista de Sistemas

## License

MIT License

Copyright (c) 2017 Danilo Righetto

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Fonte

#### [CAELUM](https://s3.amazonaws.com/caelum.com.br/caelum-arquivos-curso-web.zip)

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [Laravel]: <http://www.laravel.com.br/usando-grunt-com-laravel-e-bootstrap/>
   [Bower]: <http://www.laravel.com.br/laravel-5-1-como-instalar-o-bootstrap-usando-bower/>
   [Gulp]: <https://tableless.com.br/gulp-o-novo-automatizador/>
   [Elixir]: <https://laravel.com/docs/5.3/elixir>
   [Composer]: <https://getcomposer.org/doc/03-cli.md#install>
   [SB Admin 2]: <https://github.com/BlackrockDigital/startbootstrap-sb-admin-2>
   [Simple Sidebar]: <https://startbootstrap.com/template-overviews/simple-sidebar/>
   [SB Admin]: <https://startbootstrap.com/template-overviews/sb-admin/>
   [gentelella]: <(https://github.com/puikinsh/gentelella)>
   [colorlib]: <https://colorlib.com/polygon/gentelella/chartjs2.html>
