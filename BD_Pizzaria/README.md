# 🍕 Banco de Dados - Pizzaria

**Disciplina:** Banco de Dados
**Professor:** Prof. Dr. João Paulo Aramuni
**Instituição:** Centro Universitário Newton Paiva

---

## 📌 Descrição

Este projeto contém o **Script 1** do Banco de Dados da Pizzaria.
O script foi desenvolvido como parte dos exercícios da disciplina **Banco de Dados**, com o objetivo de aplicar conceitos de **modelagem relacional**, **criação de tabelas**, **restrições de integridade** e **manipulação de dados (DML)**.

---

## 🗂 Estrutura do Script

O script realiza:

* **Criação das Tabelas**:

  * CLIENTE
  * VENDEDOR
  * FORNECEDOR
  * PRODUTO
  * TIPO\_PRODUTO
  * FORMA\_PAGAMENTO
  * PEDIDO\_COMPRA
  * ITEM\_PEDIDO\_COMPRA
  * PEDIDO\_VENDA
  * ITEM\_PEDIDO\_VENDA
  * COTAÇÃO
  * SITUAÇÃO\_PEDIDO

* **Definição de Chaves Primárias e Estrangeiras**
  Inclui relacionamentos entre clientes, fornecedores, vendedores, produtos e pedidos.

* **Criação de Índices**
  Índices únicos foram definidos para garantir consistência dos registros.

* **Exemplos de Manipulação de Dados (DML)**
  O script possui exemplos de comandos SQL:

  * `INSERT` → inserção de registros iniciais.
  * `SELECT` → consultas simples.
  * `UPDATE` → atualização de dados.
  * `DELETE` → exclusão de registros.

---

## ⚠️ Observação Importante

Na tabela **ITEM\_PEDIDO\_VENDA**, a chave estrangeira de `COD_PEDIDO_VENDA` está referenciada incorretamente para a tabela **PEDIDO\_COMPRA**, quando deveria referenciar **PEDIDO\_VENDA**.
Esse detalhe foi mantido conforme o script original entregue, mas deve ser corrigido em futuras versões.

---

## 🚀 Objetivo

Este exercício permite praticar:

* **Modelagem de banco de dados relacional**
* **Criação e gerenciamento de tabelas**
* **Relacionamentos entre entidades**
* **Operações básicas de manipulação de dados em SQL**

---

## 📂 Conteúdo da Pasta

* `script_pizzaria.sql` → Script 1 completo do Banco de Dados da Pizzaria.

---

**Centro Universitário Newton Paiva**
Curso: Análise e Desenvolvimento de Sistemas
