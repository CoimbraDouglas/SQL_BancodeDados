# 📂 BD\_Arajet

Este diretório faz parte da disciplina **Banco de Dados**, ministrada pelo **Prof. Dr. João Paulo Aramuni**, no curso de **Análise e Desenvolvimento de Sistemas** do **Centro Universitário Newton Paiva**.

## 📌 Conteúdo da pasta

* **Diagrama Entidade-Relacionamento (DER)**

  * Arquivo em formato `.drawio`
  * Imagem exportada do diagrama, representando as entidades e seus relacionamentos.

* **Script SQL (`.sql`)**

  * Contém a criação do banco de dados **Arajet**, com as seguintes tabelas principais:

    * **FUNCIONARIO** – cadastro de colaboradores (nome, email, função).
    * **AERONAVE** – dados da frota (modelo, tipo, combustível, autonomia).
    * **PASSAGEIRO** – informações de clientes (nome, CPF, telefone).
    * **ASSENTO** – categorias e valores de assentos.
    * **PASSAGEM** – dados de voos (aeronave, passageiro, origem, destino, data, valor).
    * **ASSENTOS\_PASSAGEM** – vínculo entre assentos e passagens.
    * **PRODUTO** – produtos disponíveis (categoria, quantidade, preço).
    * **PRODUTOS\_PASSAGEM** – associação de produtos adquiridos em cada passagem.
    * **ESCALAS\_PASSAGEM** – paradas/escalas de cada voo.
    * **TRIPULACAO\_ESCALA** – alocação de funcionários em escalas específicas.

## 🎯 Objetivo

O projeto teve como objetivo:

* Modelar um **sistema de passagens aéreas** com funcionalidades de gestão de aeronaves, tripulação, passageiros e vendas de produtos.
* Explorar conceitos de **normalização, integridade referencial e modelagem de relacionamentos complexos (1\:N e N\:M)**.
* Implementar o modelo lógico em **SQL**, com **chaves primárias, estrangeiras e índices únicos**.

## 🛠️ Ferramentas utilizadas

* **Draw\.io** → para modelagem do DER.
* **SQL (DDL)** → para criação da estrutura do banco de dados.

---

📚 **Disciplina**: Banco de Dados
👨‍🏫 **Professor**: Dr. João Paulo Aramuni
🏫 **Instituição**: Centro Universitário Newton Paiva
