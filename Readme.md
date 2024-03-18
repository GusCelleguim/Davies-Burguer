# Projeto "Burgers"

O projeto "Burgers" é uma tela de exemplo para aprender conceitos de formulários em HTML e CSS, geralmente ensinado na Codecademy. Nesta tela, o cliente pode selecionar como deseja seu pedido de hambúrguer, escolhendo o tipo de proteína, a quantidade de hambúrgueres, o ponto da carne, os acompanhamentos, o tipo de queijo, o tipo de pão e o tipo de molho. Além disso, há um campo de texto para adicionar informações extras.

## Análise do Código HTML

- `<!DOCTYPE html>`: Declara que o documento é um HTML5.
- `<html lang="en" dir="ltr">`: Define o idioma do documento como inglês e a direção do texto da esquerda para a direita.
- `<head>`: Contém metadados e links para folhas de estilo e fontes.
- `<meta charset="utf-8">`: Define a codificação de caracteres como UTF-8.
- `<link rel="stylesheet" type="text/css" href="/estilo/style.css">`: Vincula uma folha de estilo CSS externa.
- `<link href="https://fonts.googleapis.com/css?family=Rubik" rel="stylesheet">`: Importa a fonte Rubik do Google Fonts.
- `<title>Forms Review</title>`: Define o título da página.
- `<body>`: Contém o conteúdo principal da página.

- `<section id="overlay">`: Uma seção que provavelmente é estilizada com CSS para criar um efeito de sobreposição.

- `<form action="submission.html" method="POST">`: Define um formulário que será enviado para "submission.html" usando o método POST.

### Detalhes do Formulário

#### Protein

- **What type of protein would you like?**
  - `input[type="text"]` para o usuário digitar o tipo de proteína.

#### Patties

- **How many patties would you like?**
  - `input[type="number"]` para o usuário escolher a quantidade de hambúrgueres.

#### Cooked

- **How do you want your patty cooked**
  - `input[type="range"]` para o usuário selecionar o ponto da carne, de _Rare_ a _Well-Done_.

#### Toppings

- **What toppings would you like?**
  - `input[type="checkbox"]` para o usuário selecionar acompanhamentos como _Lettuce_, _Tomato_ e _Onion_.

#### Cheesy

- **Would you like to add cheese?**
  - `input[type="radio"]` para o usuário escolher entre _Yes_ ou _No_.

#### Bun Type

- **What type of bun would you like?**
  - `select` com opções como _Sesame_, _Potato_, e _Pretzel_.

#### Sauce Selection

- **What type of sauce would you like?**
  - `input[list="sauces"]` para o usuário escolher um molho, com opções em `datalist` como _Ketchup_, _Mayo_, e _Mustard_.

#### Extra Info

- **Anything else you want to add?**
  - `textarea` para o usuário adicionar informações extras.

#### Submission

- `input[type="submit"]` para enviar o formulário.

---

Cada `<section>` dentro do formulário é projetada para coletar diferentes partes das preferências do pedido de hambúrguer do usuário, utilizando uma variedade de elementos de entrada para uma interação detalhada e personalizada.
