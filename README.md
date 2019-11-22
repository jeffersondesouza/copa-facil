# Copa Fácil

### Rodar Projeto

`npm install`
`npm start`

### CSS

- Não Se assuste com a quantidade de arquivos CSS! Para facilitar a manutenção foi feito uso do Atomic Design, onde cada class ganha um arquivo. Dessa forma facilita-se a manutenção e reutilização;


- Todas as classes do CSS levam o prefíxo cf(Copa Fácil, ex: cf-header) para evitar sobrescrições e conflitos nas páginas que não foram alteradas e continuam usando o bootstrap;


- Além do atomic design foi feito uso do BEM (Block, Element, Modifier) p padronizar a nomeação das classes do css. Por ex:
  - cf-btn (estilizar um botão)
  - cf-btn__label (estilizar um label que é filho __ de botão)
  - cf-btn--red (botão vermelho)
  - cf-btn-main (btn-main apenas um nome composto)


### Bootstrap
  - Como o projeto destino faz uso do Angular (ao menos foi a impressão que tive), algums componentes como Modal, Tab devem está sendo usados via libs do bootstrap, assim, mantive os modais e tabs com o bootstrap.