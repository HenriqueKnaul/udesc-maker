---
# 📝 MODELO DE PROJETO: Preencha os campos abaixo para inserir seu projeto no site.
# DICA: Não apague as aspas "" e mantenha os recuos para o site não quebrar.

visivel: false # Altere para 'true' para apresentar o projeto do site
titulo: "NOME DO SEU PROJETO AQUI"
autor: "Nome do Autor ou Equipe"
resumo: "Escreva aqui uma frase curta (máximo 150 caracteres) que resuma o projeto."
idade_minima: 10 
duracao: "2 horas" 
dificuldade: "iniciante" # Opções: iniciante, intermediario, avancado
categoria: ["Eletrônica", "Artesanato"] # Adicione ou remova categorias entre colchetes
thumbnail: "/thumbnails/layout.jpg" # Caminho da imagem que aparece na listagem --- essa imagem precisa estar na pasta [thumbnails] para maior organização.
tags: ["arduino", "maker", "escola"]
recursos: # Aqui apresenta os links e arquivos, só seguir a estrutura abaixo  
  - nome: "Manual de Montagem"
    tipo: "pdf" # Opções: pdf, codigo, link, 3d, outro
    url: "/arquivos/manual.pdf"
  - nome: "Código do Arduino"
    tipo: "codigo"
    url: "https://github.com/..."
---

## Sobre o Projeto

**DICA:** Use este espaço para inspirar! Explique o que o projeto faz e qual o principal aprendizado (ex: 'Neste projeto, vamos aprender como a energia solar se transforma em movimento').

## Materiais Necessários

* 1x Item Principal
* 1x Componente Eletrônico
* 1x Ferramenta Necessária
* 1x Insumo / Sucata

## Passo a Passo

1. **Preparação dos Materiais:** Organize todos os itens da lista acima e limpe a sua área de trabalho.
2. **Montagem da Base:** Descreva como unir as peças principais. Use frases curtas e diretas.
3. **Conexões Elétricas:** Siga o diagrama abaixo para conectar os componentes.
   ![Legenda da Imagem](/projetos/layout-base/imagem-layout.png)

4. **Programação e Teste:** Carregue o código abaixo no seu microcontrolador e verifique se o LED pisca como esperado.
   ```cpp
   // Cole seu código aqui dentro

   