# Oráculo

O **Oráculo** é uma plataforma educacional desenvolvida para alunos e professores, com foco em tecnologia e aprendizado interativo. A plataforma oferece uma biblioteca digital de livros, quizzes de TI e informações sobre a missão e a equipe que desenvolveu o projeto.

## Funcionalidades

A plataforma "Oráculo" é composta por várias páginas HTML, interligadas de forma intuitiva, proporcionando uma experiência de aprendizado completa:

### Páginas do Sistema

1. **Página Inicial (index.html)**  
   A página inicial apresenta a introdução à plataforma, com links para as seções principais do sistema, como Biblioteca, Quiz e Sobre Nós. Também inclui um vídeo explicativo e cartões informativos sobre os recursos da plataforma.
   
2. **Biblioteca (biblioteca.html)**  
   A seção Biblioteca digital contém uma vasta coleção de livros de tecnologia. O usuário pode pesquisar por pastas e visualizar os livros disponíveis. A exibição dos livros é dinâmica, gerada por JavaScript.
   
3. **Quiz (quiz.html)**  
   O Quiz interativo oferece perguntas sobre temas de tecnologia, desafiando os usuários a testarem seus conhecimentos. As perguntas variam de conceitos básicos até tópicos avançados.
   
4. **Sobre Nós (sobre.html)**  
   Apresenta informações sobre a origem e missão da plataforma, e também apresenta os membros responsáveis pelo desenvolvimento do Oráculo.

5. **Home (Home.html)**  
   Página final com um vídeo explicativo sobre a plataforma, e cartões informativos sobre os principais recursos, como a biblioteca, quizzes e o objetivo educacional.

## Estrutura do Código

O código HTML está estruturado da seguinte forma:

- **Cabeçalho (`<head>`)**: Contém as meta tags essenciais, links para os arquivos CSS, e o título da página.
- **Corpo (`<body>`)**: Dividido em **header**, **main** e **footer**. O header contém o logo e a navegação, o main exibe o conteúdo principal (como quizzes e livros), e o footer exibe informações sobre os direitos autorais e a equipe.
- **Scripts JavaScript**: Usados para adicionar interatividade às páginas, como modais para livros, quizzes interativos e navegação dinâmica.

## Responsividade

A plataforma é responsiva e utiliza **CSS Flexbox** e **media queries** para garantir que a interface se ajuste corretamente a diferentes tamanhos de tela, proporcionando uma boa experiência em dispositivos móveis e desktop.

## Modal

A seção de **Biblioteca (biblioteca.html)** utiliza um sistema de **modal** para exibir detalhes dos livros em uma pasta específica:

- O modal é inicialmente oculto (`display: none`).
- Quando o usuário clica em uma pasta, o modal é exibido com os livros contidos nela.
- O modal pode ser fechado ao clicar no botão de fechar (`&times;`).

## Tecnologias Utilizadas

- **HTML**: Estruturação das páginas.
- **CSS**: Estilos para a interface.
- **JavaScript**: Funcionalidades interativas, como quizzes e modais.

## Equipe de Desenvolvimento

A plataforma foi desenvolvida por três aprendizes em TI:

- **Rudson Martins Botelho**
- **Willian Barbosa Roscoe**
- **Vinícius Andrade**

## Como Executar o Projeto

1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/seuusuario/oraculo.git

