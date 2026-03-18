---
title: Meu ferramentário pessoal desenvolvido em 2025
description: Ao longo de 2025 eu construí todo um arsenal de ferramentas para usar no meu dia-dia visando substituir minha dependência do Notion para tudo por um aplicação própria, e nesse post eu abordo tudo sobre a construção desses serviços.
slug: ferramentario
date: 2026-03-02 00:00:00+0000
# image: cover.jpg
categories:
    - Tecnologia
tags:
    - Misc
weight: 0       # You can add weight to some posts to override the default sorting (date descending)
---

# Introdução
Ao longo de 2025 eu construí todo um arsenal de ferramentas para usar no meu dia-dia visando substituir minha dependência do Notion para tudo por um aplicação própria, e nesse post eu abordo tudo sobre a construção desses serviços.

Ao total foram 4 "aplicações" diferentes, sendo duas delas serviços de fato, e as outras duas ferramentas para viabilizar o uso desses serviços, que poderão ser reutilizados em outros projetos:
- Uma API para gerenciar e guardar meus logins e senhas
- Um gerenciador de finanças
- Um IDP lightweight desenvolvido em Go para gerenciar meu acesso às aplicações
- Uma CLI para acessar/manipular tudo isso.

Os serviços são muito simples, por mais que o "ecossistema" possua bastante "overengineering" proposital (como o IDP e CLI), visto que, como abordarei abaixo, as aplicações foram desenvolvidas para fins de estudo/hobby.

Todas as aplicações desenvolvidas nesse projeto foram documentadas em forma de vídeo e estão disponíveis no meu canal do [Youtube](https://youtube.com/@RopehapiCoding).

## As motivações
A muitos anos, antes mesmo de virar moda em 2021, eu utilizo o Notion para administrar toda a minha vida, desde coisas simples como calendário e tarefas do dia-dia a um controle financeiro completíssimo que me permite acompanhar toda a minha saúde monetária. E com o passar dos anos, ao longo do meu uso intenso da ferramenta, eu fui percebendo algumas limitações/red-flags, principalmente na forma como os dados armazenados ficam engessados para a manipulação e a segurança disso. Outra coisa que me irrita, é o fato de eu ter que estar o tempo todo em contato com uma GUI (Graphical user interface) para manipular meus dados, clicando com o mouse pra lá e pra cá, o que eu não acho nada prático, visto que sou adepto do ecossistema Linux a muitos anos e sou um hard-user de CLIs.

Baseado nisso, e também atrás de uma pulga para me coçar, decidi construir eu mesmo meu próprio ecossistema de ferramentas para substituir minha dependência do notion. Gerando dados que podem ser tratados e protegidos de maneira muito mais eficiente.

Muitas são as perguntas que eu posso receber ao falar sobre um ecossistema desses, desenvolvido em casa, para realizar tarefas triviais como guardar senhas e gerenciar finanças, como: "Pra que isso? Não existe um aplicativo que faça isso?", ou "X software não faz isso pra você e muito melhor?". E para responder essas perguntas, nós vamos partir da premissa de que os projetos foram desenvolvidos mais para fins de estudo, logo, qualquer "overegineer" por ser respondida também com um "eu quis fazer pra aprender".

# Desenvolvimento
Abaixo, abordarei um pouco sobre o desenvolvimento de cada serviço individualmente. Começando pelos serviços de fato, e depois as ferramentas de apoio a esses serviços.

## O primogênito: password-vault

## O segurança dessa festa: O IDP

## O cara que cuida do meu dinheiro: O finance-manager

## E como vamos usar tudo isso? Prazer, rphpctl



