---
title: Meu ferramentário pessoal desenvolvido em 2025
description: Ao longo de 2025 eu construí todo um arsenal de ferramentas para usar no meu dia-dia visando substituir minha dependência do Notion para tudo por um self-host, e nesse post eu abordo tudo sobre a construção desses serviços.
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
Ao longo de 2025 eu construí todo um arsenal de ferramentas para usar no meu dia-dia visando substituir minha dependência do Notion para tudo por um self-host, e nesse post eu abordo tudo sobre a construção desses serviços.

Ao total foram 4 "aplicações" diferentes, sendo duas delas serviços de fato, e as outras duas ferramentas para viabilizar o uso desses serviços:
- Um IDP lightweight desenvolvido em Go para gerenciar meu acesso às aplicações
- Uma API para gerenciar e guardar meus logins e senhas
- Um gerenciador de finanças
- Uma CLI para acessar/manipular tudo isso.

O "ecossistema" possui bastante "overengineering" proposital, visto que, como abordarei abaixo, as aplicações foram desenvolvidas para fins de estudo/hobby.

# As motivações
Muitas são as perguntas que eu posso receber ao falar sobre um ecossistema desses, desenvolvido em casa, para realizar tarefas triviais como guardar senhas e gerenciar finanças. A primeira delas sendo: "Pra que isso? Não existe um aplicativo que faça isso?", ou "X software não faz isso pra você e muito melhor?", e a segunda: "Porque você quer fazer você mesmo a hospedagem e custódia desses dados/serviços? Ao manter no Notion você tem tudo isso na cloud e backupeado pra você". E para responder essas perguntas, nós vamos partir de algumas premissas, sendo elas: 
- Eu gosto de escrever código, é meu hobby, então eu só quis fazer e ponto.
- Eu sempre vou preferir fazer as coisas eu mesmo, é muito chato pagar para que os outros façam por você.

