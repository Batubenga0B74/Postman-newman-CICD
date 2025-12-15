# 🧪 Petstore API – CI/CD Practice

Este repositório é uma **prática de automação de testes de API** utilizando a **Swagger Petstore (API pública)**, com foco em **CI/CD para QA / QA Ops**.

O objetivo é demonstrar como **testes manuais feitos no Postman** podem ser **automatizados** e **executados automaticamente em pipeline CI** usando **Newman + GitHub Actions**, com geração de **relatórios HTML**.

---

## 🎯 Objetivo da prática

* Testar uma **API pública (Petstore)**
* Automatizar testes de API com **Postman**
* Executar os testes em **CI/CD**
* Gerar **relatórios HTML** com Newman
* Simular um cenário real de **QA em ambiente profissional**

---

## 🛠️ Tecnologias e ferramentas

* **Postman** – Criação dos testes de API
* **Newman** – Runner de collections Postman
* **newman-reporter-htmlextra** – Relatórios HTML
* **GitHub Actions** – Pipeline CI/CD
* **Node.js** – Ambiente de execução

---

## 📂 Estrutura do projeto

```
.
├── pepstore.postman_collection.json
├── .github/
│   └── workflows/
│       └── api-tests.yml
└── README.md
```

---

## 🧪 Testes implementados

Os testes cobrem exemplos como:

* Validação de **status code**
* Validação de **tempo de resposta**
* Validação de **estrutura da resposta (schema)**
* Testes em endpoints da Petstore como:

  * `GET /pet/{id}`
  * `POST /pet`
  * `DELETE /pet/
