# Valida-CPF

Este é um projetinho simples em HTML, CSS e JavaScript que permite ao usuário digitar um CPF e verificar se ele é válido ou não, com uma resposta visual clara.

## Funcionalidades

- Entrada de CPF pelo usuário.
- Validação automática dos dígitos verificadores do CPF.
- Mensagem de sucesso ou erro na tela.

## Tecnologias usadas

- HTML
- CSS
- JavaScript

## Como usar

1. Abra o arquivo `index.html` em seu navegador.
2. Digite um CPF no campo indicado.
3. Clique no botão "Verificar".
4. A mensagem de "CPF Válido" ou "CPF Inválido" aparecerá na tela.

## Sobre a Validação

O script segue as regras oficiais da Receita Federal para validar CPFs:
- Elimina caracteres não numéricos.
- Verifica se todos os dígitos são iguais (ex: `111.111.111-11`, que é inválido).
- Calcula e valida os dois dígitos verificadores.

## Observações

- O campo aceita somente a entrada numérica, mas o script limpa automaticamente qualquer caractere inválido.
- A classe `message` possui estilos de sucesso e erro bem definidos no CSS.