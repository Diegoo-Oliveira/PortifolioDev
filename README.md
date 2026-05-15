# Portifolio Dev

Projeto de portfolio pessoal desenvolvido durante os estudos da Rocketseat.
A proposta e recriar o layout "Portfolio Dev" do Figma usando HTML e CSS, com
uma estrutura organizada para facilitar comparacoes futuras com o codigo do
professor.

## Status

Layout principal em desenvolvimento avancado.

No momento, o projeto ja possui a estrutura HTML das quatro secoes principais e
os estilos separados por responsabilidade: base global, intro, projetos,
servicos, contato e utilitarios. A pagina esta montada para o layout desktop do
Figma, com largura de referencia em `1366px`.

## Objetivo

Construir uma pagina de portfolio em tema escuro com:

- apresentacao inicial com foto, nome, titulo e descricao;
- lista de tecnologias usadas;
- secao "Meu trabalho" com seis projetos em destaque;
- secao "Meus servicos" com cards de servicos;
- secao final de contato com links sociais.

## Tecnologias

- HTML
- CSS

## Estrutura da pasta

```txt
PortifolioDev/
  index.html
  index.css
  README.md
  Assets/
    icons/
      CSS.svg
      GitHub.svg
      HTML.svg
      JavaScript.svg
      Node.js.svg
      React.svg
      discord-logo.svg
      Portfolio Dev (Community).zip
    img/
      Background_Contacts.png
      Background_Intro.png
      Thumbnail_Project-01.png
      Thumbnail_Project-02.png
      Thumbnail_Project-03.png
      Thumbnail_Project-04.png
      Thumbnail_Project-05.png
      Thumbnail_Project-06.png
  styles/
    contact.css
    global.css
    intro.css
    projects.css
    services.css
    utility.css
```

## Arquivos principais

`index.html`

Arquivo principal da pagina. Contem a estrutura das secoes `intro`, `projects`,
`services` e `contact`, alem dos cards, tags de tecnologias e links sociais.

`index.css`

Arquivo de entrada dos estilos. Ele importa os arquivos CSS separados dentro da
pasta `styles`.

`styles/global.css`

Arquivo com reset, tokens de cor, fontes, classes de texto e configuracoes
principais das secoes.

`styles/intro.css`

Arquivo com os estilos da apresentacao inicial, avatar, textos e tecnologias.

`styles/projects.css`

Arquivo com os estilos dos cards de projeto e espacamento da secao "Meu
trabalho".

`styles/services.css`

Arquivo com os estilos dos cards da secao "Meus servicos".

`styles/contact.css`

Arquivo com os estilos da secao final de contato e dos botoes sociais.

`styles/utility.css`

Arquivo com classes utilitarias de flex, grid e gaps reutilizados nas secoes.

`Assets/img`

Pasta com os backgrounds e thumbnails dos seis projetos que aparecem no layout.

`Assets/icons`

Pasta com os icones das tecnologias e links sociais.
