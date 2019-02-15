---
layout: post
title:  "Listando conteúdo de um Endpoint"
date:   2019-02-15 10:18:00
categories: Desenvolvimento Front end
---
Hoje vou compartilhar com você mais uma criação para fins acadêmicos onde foi realizado um desafio que consistiu na implantação de um site que onde listava o conteudo (cursos) utilizando um endpoint de uma API já implantada. E uma página  de exibição do conteúdo  do curso selecionado.

 Os seguintes critérios foram adotados:
 - Os cursos deverão ser buscados em uma requisição ajax no endpoint https://cefis.com.br/api/v1/event)
 - A resposta é um json que contém um array de objetos que representam cada curso.
 - o formato da resposta é um json que contém um de objeto que representa o curso.
 - Para cada curso na listagem, deve ser mostrado no mínimo o título e o banner.
 - Para a página específica de exibição de um único curso, deve ser mostrado no mínimo
o título, o banner e o título das aulas.
- A página de exibição de um único curso deve ser genérica para qualquer curso.
- Não é necessário implementar uma aplicação em servidor para retornar as páginas
HTML.

Foi adotado o uso do JQuery para desenvolver o acesso e manipulação da API.
O código desenvolvido  está nesse repositório: https://github.com/Tvitor/DesafioCursos
    - E hospedado nesse endereço: https://tvitor.github.io/DesafioCursos/
    





