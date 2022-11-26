<p>
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rafaelftourinho/mysql_all_for_one?color=6E40C9&style=flat-square">
  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/rafaelftourinho/mysql_all_for_one?color=6E40C9&style=flat-square">
  <a href="https://github.com/rafaelftourinho/mysql_all_for_one/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rafaelftourinho/mysql_all_for_one?color=6E40C9&style=flat-square">
  </a>
</p>

# Boas vindas ao repositório do projeto All For One

<div align="center">
  <img height="150px" align="right" src="https://theme.zdassets.com/theme_assets/9633455/9814df697eaf49815d7df109110815ff887b3457.png" />
  <div align="left" style="display: inline_block">
    <h2>Módulo: DESENVOLVIMENTO BACK-END</h2>
    <p>
      Repositório possuí projeto desenvolvido no período que estive na <b>Trybe</b>, abordando os conceitos de <b>SQL</b> e seus comandos.
  </div>
  <br>
</div>

## Habilidades

- Entender o que são bancos de dados
- Entender como a linguagem de consulta estruturada (SQL) é usada
- Compreender como as tabelas se encaixam no conceito de banco de dados
- Montar um ambiente de desenvolvimento local para praticar SQL
- Entender como usar o MySQL Workbench
- Compreender o que é uma query SQL e quais são seus tipos de comando
- Gerar valores com SELECT
- Selecionar colunas individualmente com SELECT
- Renomear e gerar colunas em uma consulta com AS
- Concatenar colunas e valores com CONCAT
- Remover dados duplicados em uma consulta com DISTINCT
- Contar a quantidade de resultados em uma consulta com COUNT
- Limitar a quantidade de resultados em uma consulta com LIMIT
- Pular resultados em uma consulta com OFFSET
- Ordernar os resultados de uma consulta com ORDER BY
- Filtrar resultados de consultas com o WHERE
- Utilizar operadores booleanos e relacionais em consultas
- Criar consultas mais dinâmicas e maleáveis com LIKE
- Fazer consultas que englobam uma faixa de resultados com IN e BETWEEN
- Encontrar e separar resultados que incluem datas.
- Inserir dados em tabelas com INSERT
- Atualizar dados em tabelas com UPDATE
- Apagar dados em tabelas com DELETE

## O que foi desenvolvido

Um projeto com o codinome All For One em que teve pratica, todos os conceitos de SQL ensinados até aqui. Porém, foi usadoar um banco de dados totalmente diferente.

---

## Instruções para instalar e rodar os testes de cada requisito

```bash
# Clone o repositório
  git clone git@github.com:rafaelftourinho/mysql_all_for_one.git
# Entre na pasta do repositório que você acabou de clonar:
  cd mysql-all-for-one
# Instale as dependências e inicialize o projeto
  npm install
# Entre no Vs Code para verificar os arquivos usando o atalho no terminal:
  code .
#  A pasta tests contém os testes que verifica se os comandos estão atendendo o que foi pedido
# Leia os Requisitos do Projeto logo abaixo explicando o que cada requisito propõem
# Para rodar os tests use o atalho no terminal:
  npm run test
```

## Requisitos do projeto

<details>

Monte queries para encontrar as informações esperadas pelos desafios:

### Desafios Iniciais

#### 1 - Exiba apenas os nomes do produtos na tabela `products`.

#### 2 - Exiba os dados de todas as colunas da tabela `products`.

#### 3 - Escreva uma query que exiba os valores da coluna que representa a primary key da tabela `products`.

#### 4 - Conte quantos registros existem na coluna `product_name` da tabela `products`.
#### 5 - Monte uma query que exiba os dados da tabela `products` a partir do quarto registro até o décimo terceiro.

**Observações técnicas**
 - Tanto o quarto quanto o décimo terceiro registros, precisam aparecer na consulta.
 - Não use `where` ou `order by`.

#### 6 - Exiba os dados das colunas `product_name` e `id` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.

#### 7 - Mostre apenas os ids dos 5 últimos registros da tabela `products` (a ordernação deve ser baseada na coluna `id`).
#### 8 - Faça uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'. 

**Observações técnicas**
 - Na primeira coluna, exiba a soma de `5 + 6` (essa soma deve ser realizada pelo SQL). 
 - Na segunda coluna deve haver a palavra \"de\". 
 - E por fim, na terceira coluna, exiba a soma de `2 + 8` (essa soma deve ser realizada pelo SQL). 
 - A primeira coluna deve se chamar \"A\", a segunda coluna deve se chamar \"Trybe\" e a terceira coluna deve se chamar \"eh\". 
 - Não use colunas pre-existentes, apenas o que for criado na hora.

---

## Desafios sobre filtragem de dados

#### 9 - Mostre todos os valores de `notes` da tabela `purchase_orders` que não são nulos.

#### 10 - Mostre todos os dados da tabela `purchase_orders` em ordem decrescente, ordenados por `created_by` em que o `created_by` é maior ou igual a 3.

**Observações técnicas**
 - Como critério de desempate para a ordenação, ordene também os resultados pelo `id` de forma crescente.

#### 11 - Exiba os dados da coluna `notes` da tabela `purchase_orders` em que seu valor de `Purchase generated based on Order` é maior ou igual a 30 e menor ou igual a 39.

#### 12 - Mostre as `submitted_date` de `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.

#### 13 - Mostre o `supplier_id` das `purchase_orders` em que o `supplier_id` seja 1 ou 3.

#### 14 - Mostre os resultados da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` seja maior ou igual a 1 e menor ou igual 3.

#### 15 - Mostre somente as horas (sem os minutos e os segundos) da coluna `submitted_date` de todos registros da tabela `purchase_orders`.

**Observações técnicas**
 - Chame essa coluna de `submitted_hour`.

#### 16 - Exiba a `submitted_date` das `purchase_orders` que estão entre `2006-01-26 00:00:00` e `2006-03-31 23:59:59`.

#### 17 - Mostre os registros das colunas `id` e `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.

#### 18 - Mostre todos os registros de `purchase_orders` que tem o `supplier_id` igual a 3 e `status_id` igual a 2.

#### 19 - Mostre a quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método(coluna) `shipper_id` igual a 2.

**Observações técnicas**
 - Chame a coluna de `orders_count`.

---

## Desafios de manipulação de tabelas

#### 20 - Adicione à tabela `order_details` um registro com `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129.

**Observações técnicas**
 - Obs.: o `id` deve ser incrementado automaticamente.

#### 21 - Adicione com um único `INSERT`, duas linhas à tabela `order_details` com os mesmos dados do requisito 20.

**Observações técnicas**
 - Esses dados são novamente `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129.
 - O `ìd` deve ser incrementado automaticamente.

#### 22 - Atualize os dados de `discount` do `order_details` para 15. (Não é necessário utilizar o SAFE UPDATE em sua query).

#### 23 - Atualize os dados da coluna `discount` da tabela `order_details` para 30, onde o valor na coluna `unit_price` seja menor que 10.0000.

**Observações técnicas**
 - Não é necessário utilizar o SAFE UPDATE em sua query.

#### 24 - Atualize os dados da coluna `discount` da tabela `order_details` para 45, onde o valor na coluna `unit_price` seja maior que 10.0000 e o id seja um número entre 30 e 40.

**Observações técnicas**
 - Não é necessário utilizar o SAFE UPDATE em sua query.

#### 25 - Delete todos os dados em que a `unit_price` da tabela `order_details` seja menor que 10.0000.

#### 26 - Delete todos os dados em que a `unit_price` da tabela `order_details` seja maior que 10.0000.

#### 27 - Delete todos os dados da tabela `order_details`.

</details>

---

<div align="left">
  <a href="https://github.com/marlondlacerda/trybe-projetos">Voltar para o repositório principal</a>
</div>
<div align="center">

  [⬆ Voltar para o topo](#boas-vindas-ao-repositório-do-projeto-all-for-one-)
