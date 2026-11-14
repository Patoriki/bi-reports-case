# BI Reports: Portal de Acesso aos Painéis de BI

> Estudo de caso. O código-fonte é privado e pertence à **RJF Consultoria**. Este repositório apresenta o projeto e a minha participação nele. As imagens usam **dados fictícios**.

## O problema
A empresa tem vários painéis de BI com indicadores de áreas e clientes diferentes. Sem um controle central, fica difícil garantir que cada pessoa veja **apenas os painéis que lhe dizem respeito** e organizar onde cada relatório fica.

## A solução
O **BI Reports** é um portal web que centraliza a visualização dos painéis de BI da empresa:
- **Login e controle de acesso**: cada usuário ou perfil vê só os painéis liberados para ele
- **Cadastro e organização dos painéis** por área ou cliente
- **Visualização incorporada**: os relatórios abrem dentro do portal, sem o usuário precisar acessar a ferramenta de BI diretamente
  <!-- confira se a lista corresponde às funcionalidades reais; se usar Power BI Embedded ou outra ferramenta, cite aqui -->

## Arquitetura
```
[ Portal web ]  ←  Angular
       │
  API REST (.NET / C#)  ──►  Ferramenta de BI (relatórios incorporados)
       │
  SQL Server (usuários, perfis e permissões)
```
<!-- ajuste a stack se for diferente -->

## Minha participação
<!-- descreva o que você fez, por exemplo:
- Desenvolvimento do portal e da tela de login
- Implementação do controle de permissões por usuário/perfil
- Integração com a ferramenta de BI para exibir os painéis
-->

## Tecnologias
C# · .NET · Angular · TypeScript · SQL Server <!-- + ferramenta de BI -->

## Telas
<!-- prints com dados fictícios na pasta /prints -->
