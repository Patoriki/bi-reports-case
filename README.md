# BI Reports: Portal de BI com Controle de Acesso por Perfil

> Estudo de caso. O código-fonte é privado e pertence à **RJF Consultoria**. Este repositório apresenta o projeto e a minha participação nele. As imagens usam **dados fictícios**.

## O problema
A empresa tem muitos painéis de BI, com indicadores de áreas e clientes diferentes. Sem um controle central, fica difícil organizar esses painéis e garantir que cada pessoa veja **apenas o que tem permissão para ver**.

## A solução
O **BI Reports** é um portal que centraliza todos os painéis de BI da empresa:
- 📊 **Armazena qualquer tipo de BI** em um só lugar
- 🔐 **Controle de acesso por perfil**: o administrador autoriza ou bloqueia cada perfil para cada painel
- 👁️ Cada usuário vê **somente os BIs liberados** para o seu perfil

## Como funciona
```
[ Administrador ] ──► define quais perfis podem ver cada BI
                               │
[ Usuário faz login ] ──► perfil ──► lista só os BIs autorizados ──► visualização
```

## Minha participação
- **Criei 100% do layout e da interface** do portal (autoria própria)
- Desenvolvimento do **front-end** em HTML5, com telas de login, listagem de painéis, visualização e gestão de permissões por perfil
- Participação pontual no back-end

## Tecnologias (front-end)
HTML5 · CSS3 · JavaScript · Bootstrap · Font Awesome · SweetAlert2

## Telas
<!-- prints com dados fictícios na pasta /prints -->
