# Exercicio de Conversao: SASS para LESS

Este repositório contém um exercício simples onde um projeto originalmente estilizado com SASS foi convertido para LESS. O objetivo é praticar e compreender os conceitos de LESS, incluindo o uso de variáveis, mixins, mapas e importações.

## Estrutura do Projeto
A estrutura de pastas do repositório é organizada da seguinte forma:

```
/
├── build/
│   ├── main.css  # Arquivo CSS gerado a partir dos arquivos LESS
│
├── src/
│   ├── img/  # Imagens do projeto
│   ├── style/  # Arquivos LESS organizados
│       ├── main.less  # Arquivo principal que importa os outros LESS
│       ├── layout.less  # Estilos gerais da estrutura da página
│       ├── produtos.less  # Estilos da seção de produtos
│       ├── mixins.less  # Mixins reutilizáveis
│       ├── variaveis.less  # Variáveis do projeto
│       ├── maps.less  # Mapa de cores do projeto
│
├── .gitattributes  # Configuração de atributos para o Git
├── .gitignore  # Arquivos e pastas ignorados pelo Git
├── index.html  # Arquivo HTML principal do projeto
```

## Como Compilar os Arquivos LESS
Para compilar os arquivos LESS e gerar o CSS final, utilize o seguinte comando:

```sh
lessc src/style/main.less build/main.css
```

Caso queira configurar a compilação automática, você pode usar ferramentas como Gulp ou scripts npm.

## Tecnologias Utilizadas
- HTML
- LESS
- Node.js (para compilação do LESS, opcional)
- Git/GitHub

## Objetivo
Este exercício tem como foco a prática de LESS e o entendimento das diferenças entre SASS e LESS na estruturação de estilos para projetos web.

---

Se tiver dúvidas ou quiser sugerir melhorias, fique à vontade para abrir uma **issue** ou enviar um **pull request**! 🚀

