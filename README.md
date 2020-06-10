# Bem-Vindo ao APP ECOLETA

Este é o **APP EColeta**, um sistema construído para unir empresas ecologicamente responsáveis com pessoas que querem colaborar com a coleta ecológica de Lixo.
Foi desenvolvido durante a **Next Level Week**, uma semana da [Rocket Seat](https://rocketseat.com.br/) focada em React, JavaScript, NODE.js e TypeScript, além de algumas bibliotecas para o React, como a Leaflet que possibilita a utilização de Mapas interativos (Semelhante ao Google Maps).

## Front-End
O Front-End foi desenvolvido em React, JavaScript e TypeScript e é claro o bom e velho HTML e CSS.

Utilize o comando `npm start` na pasta `web`para iniciar o ambiente Front-End.

Página Inicial, com informações do projeto e botão para fazer o cadastro do ponto de coleta.

![Página Principal](https://github.com/G-Ataide/app-coleta/blob/master/imgs/web/1.png?raw=true "Página Principal")


Página para Cadastro dos Pontos de Coleta

![Página Cadastro](https://github.com/G-Ataide/app-coleta/blob/master/imgs/web/2.png?raw=true "Página de Cadastro")

## Back-End
Foram desenvolvidas API's Restful, utilizando NODE.js para fazer os cadastros e consultas dos pontos de coletas. Para gravar as informações, foi utilizado o banco  de dados SQLite 

Utilize o comando `npm run dev` na pasta `server`para iniciar o ambiente Back-End.

![NODE e conexão com SQLite](https://github.com/G-Ataide/app-coleta/blob/master/imgs/server/1.png?raw=true "NODE e conexão com SQLite")

## Mobile
O Mobile foi desenvolvido em React Native e utilizando a ferramenta EXPO.

Utilize o comando `npm start` na pasta `mobile`para iniciar o ambiente Mobile.

Página Inicial para buscar Pontos de Coleta por Endereço (Cidade e Estado)

![Página Inicial](https://github.com/G-Ataide/app-coleta/blob/master/imgs/mobile/1.png?raw=true "Página Inicial")

Página Secundária, mostrando a localização real de cada ponto de coleta, utilizando Google Maps (Android) e Apple Maps (iOS). Nesta página podemos filtrar os tipos de itens à serem descartados.

![Página Secundária](https://github.com/G-Ataide/app-coleta/blob/master/imgs/mobile/2.png?raw=true "Página Secundária")

Clicando na foto do Ponto de Coleta, somos redirecionados a página de detalhes do Ponto de Coleta, com Foto, Descrição, Endereço e Botões para fazer contato via WhatsApp e E-mail.

![Página Informações](https://github.com/G-Ataide/app-coleta/blob/master/imgs/mobile/3.png?raw=true "Página Informações")
