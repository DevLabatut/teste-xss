## Teste XSS — innerHTML vs innerText vs textContent

Projeto simples em HTML com JavaScript embutido para demonstrar as diferenças entre innerHTML, innerText e textContent. O exemplo mostra como entradas do usuário podem impactar a página e evidenciar riscos básicos de XSS (Cross-Site Scripting).

## Preview

<img src="preview.png" width="400">

## Funcionalidades

* Campo para digitação de texto pelo usuário.
* Exibição do resultado usando:

  * `innerHTML`
  * `innerText`
  * `textContent`
* Validação simples de campo vazio.
* Demonstração prática de como conteúdo pode ser interpretado como HTML.

## Tecnologias

* HTML5
* CSS
* JavaScript puro (sem bibliotecas externas)

## Estrutura do Projeto

```
teste-xss/
│
├─ preview.png
└─ index.html
```

## Como usar

Clone o repositório:

```
git clone https://github.com/DevLabatut/teste-xss.git
```

Entre na pasta do projeto:

```
cd teste-xss
```

Abra o arquivo no navegador:

```
index.html
```

Digite qualquer conteúdo e clique em **Testar** para ver a diferença entre os métodos.

## Observações

* Projeto feito apenas para aprendizado e demonstração.
* Não possui backend ou armazenamento de dados.
* Ideal para entender riscos básicos ao inserir conteúdo em páginas web.
* Nunca utilize `innerHTML` com dados do usuário sem validação ou sanitização.

## Autor

| [<img src="https://github.com/DevLabatut.png" width=115><br><sub>DevLabatut</sub>](https://github.com/DevLabatut) |
| :---------------------------------------------------------------------------------------------------------------: |


