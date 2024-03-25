# Customer Success Balancing

Este é um projeto que implementa uma função para balanceamento de clientes entre gerentes de sucesso do cliente (Customer Success).

## Premissas
Sendo n o número de CSs, m o número de clientes e t o número de abstenções de CSs, calcular quais clientes serão atendidos por quais CSs de acordo com as regras apresentadas
- Todos os CSs têm níveis diferentes
- Não há limite de clientes por CS
- Clientes podem ficar sem serem atendidos
- Clientes podem ter o mesmo tamanho
- 0 < n < 1.000
- 0 < m < 1.000.000
- 0 < id do cs < 1.000
- 0 < id do cliente < 1.000.000
- 0 < nível do cs < 10.000
- 0 < tamanho do cliente < 100.000
- Valor máximo de t = n/2 arredondado para baixo

### Pré-requisitos

Certifique-se de ter o Node.js e o npm instalados em seu sistema.

### Instalação

Clone este repositório:

## Versão Node utilizada

- Node 20.11.1

## Versão do JavaScript utilizada

- ES6+

```sh
git clone https://github.com/igoormatias/customerSuccessBalacing.git
```

Acesse o diretório do projeto:

```sh
cd customerSuccessBalacing
```

Instale as dependências:

```sh
npm install
```

## Como usar

Verificar os casos de testes:

```sh
npm run test
```
