# SiteUniesp

O React é uma biblioteca que tem como finalidade facilitar a criação de projetos.
O grande diferencial do React é o uso de componentes que tem como objetivo a reutilização do código, gerando uma maior produtividade.


Para iniciarmos um projeto React, utilizamos no terminal da IDE o comando “npm create vite@latest”, configuramos o projeto e logo após configurar usamos o comando “npm install”, o NPM (node package manager)  é um gerenciador de pacotes node.


Nosso projeto Site Uniesp está dividido em pastas, cada uma com uma finalidade específica.

“src” é uma das pastas principais de nosso projeto, onde ficam os códigos desenvolvidos.
Dentro de “src” temos:

   “assets”: é a pasta onde armazenamos imagens, fontes etc de forma privada.

   “components”: é onde ficam armazenados os componentes de nosso projeto, aquele código que iremos reutilizar sem precisar ficar criando outros arquivos, evitando um retrabalho.
   Dentro de components temos os arquivos BannerAd.jsx para a propaganda e a NavBar.jsx para a nossa barra superior. Ambas estão sendo usadas em todas as páginas sem a necessidade de serem reescritas.

   “pages”: onde ficam as nossas páginas do projeto. Temos as paginas DpoLgpd, Noticias, Faculdade, Inicial e Visualizar Noticias. Todas sendo devidamente roteadas no App.jsx e podendo ser utilizadas clicando na barra superior (NavBar).
   
   “admin”: funcionalidades dos admins.


“data”: na pasta data nós criamos um Banco de Dados falso, utilizando o arquivo db.json.

“node modules”: onde ficam todos os arquivos criados pelo npm install.

“public”: onde armazenamos imagens de forma pública.

Ainda dentro de src temos o arquivo “App.jsx”, sendo ele o nosso arquivo “pai”, onde iremos chamar todos os componentes e fazer o roteamento para cada página.
Também dentro de src, temos os arquivos “app.css” e “main.css” para a estilização do projeto, porém não utilizamos ele, optamos pela biblioteca Mui para a estilização.

Dentro de nosso projeto porém fora de pastas, temos os arquivos:
	
   “.gitignore” para o git ignorar o que queremos.
	
   “eslint.config.js” para algumas configurações do projeto.

   “index.html” onde configuramos nosso HTML e também chamamos nossos scripts.

   “package-lock.json” e “package.json": onde temos todas as nossas dependências e bibliotecas instaladas, além de algumas configurações do node.
   
   “README.md”: para escrevermos sobre o projeto
	
   “vite.config.js”: para as configurações do VITE.



Bibliotecas utilizadas:

  Mui: É uma biblioteca focada em facilitar a estilização.
	npm install @mui/material @emotion/react @emotion/styled
	npm install @mui/icons-material --legacy-peer-deps

  Axios: Biblioteca muito utilizada para fazer requisições HTTP. Permite que você envie ou receba dados de forma assíncrona
	npm install axios

  React Router Dom: Biblioteca utilizada para criação de rotas, ou seja, mapeia URLs para componentes específicos, sem que a página precise ser recarregada..
	npm install react-router-dom


