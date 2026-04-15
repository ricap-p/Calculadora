# Calculadora Web

Projeto simples de calculadora desenvolvido com HTML, CSS e JavaScript.

## Funcionalidades

* Soma
* Subtração
* Multiplicação
* Divisão
* Limpar display
* Exibição do resultado
* Tratamento de erro para contas inválidas

## Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript

## Estrutura do projeto

```text
projeto/
│
├── index.html
├── style.css
└── calculadora.js
```

## Como funciona

A calculadora utiliza:

* HTML para estruturar os botões e display
* CSS para estilização
* JavaScript para lógica e manipulação do DOM

### Principais funções JavaScript

```javascript
function appendToDisplay(value)
```

Responsável por adicionar números e operadores no display.

```javascript
function clearDisplay()
```

Responsável por limpar o display.

```javascript
function calculateResult()
```

Responsável por calcular a expressão digitada usando `eval()`.

## Como executar

1. Baixe os arquivos
2. Abra a pasta do projeto
3. Execute o arquivo `index.html` no navegador

## Melhorias futuras

* Adicionar botão de porcentagem
* Adicionar botão de apagar último número
* Adicionar suporte a teclado
* Melhorar responsividade
* Adicionar modo claro e escuro

## Autor

Ricardo Prudencio
