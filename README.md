# 📚 Aula 07 — Frameworks Front-end

> 💻 Resumo interativo dos conteúdos da Aula 07: APIs, comunicação HTTP, JSON, criação de API REST com Express e frameworks CSS.

👨‍🏫 **Professor:** Me. Deivison S. Takatu  
📧 **E-mail:** [deivison.takatu@edu.senai.br](mailto:deivison.takatu@edu.senai.br)  
🎓 **Disciplina:** Frameworks Front-end

## 🧭 Sumário

1. [🔌 API (Application Programming Interface)](#1-api-application-programming-interface)
2. [🌐 Protocolo HTTP](#2-protocolo-http)
3. [🎯 Endpoint](#3-endpoint)
4. [📦 JSON (JavaScript Object Notation)](#4-json-javascript-object-notation)
5. [📝 Atividade 01](#5-atividade-01)
6. [🖥️ Servidor backend e Web Service](#6-servidor-backend-e-web-service)
7. [🚀 Criando uma API REST com Express](#7-criando-uma-api-rest-com-express)
8. [🧪 Atividade 02](#8-atividade-02)
9. [🎨 Cascading Style Sheets (CSS)](#9-cascading-style-sheets-css)
10. [🔗 Projetos relacionados](#10-projetos-relacionados)

## 1. 🔌 API (Application Programming Interface)

Uma **API** é uma interface que permite a comunicação entre sistemas. Ela recebe uma solicitação do cliente — por exemplo, uma aplicação front-end —, encaminha o pedido ao serviço responsável e devolve uma resposta.

Uma analogia é a de um aplicativo de delivery: o aplicativo envia o pedido ao restaurante e recebe informações sobre o andamento, sem precisar conhecer os processos internos do estabelecimento.

Essa comunicação promove o **desacoplamento** entre as partes. O front-end pode ser desenvolvido com React ou Vue, por exemplo, enquanto o back-end utiliza Node.js ou Python, desde que ambos sigam um contrato de comunicação comum.

## 2. 🌐 Protocolo HTTP

O **HTTP** (Hypertext Transfer Protocol) define regras para a troca de informações entre clientes, como navegadores e aplicações, e servidores.

Os principais métodos HTTP são:

| Método | Uso comum |
| --- | --- |
| `GET` | Consultar ou listar dados |
| `POST` | Enviar dados para criar um recurso |
| `PUT` | Substituir ou atualizar um recurso |
| `PATCH` | Atualizar parcialmente um recurso |
| `DELETE` | Remover um recurso |

Por exemplo, uma aplicação pode usar `GET` para consultar produtos e `POST` para cadastrar um novo produto.

## 3. 🎯 Endpoint

Um **endpoint** é um endereço específico de uma API usado para acessar determinado recurso ou executar uma operação.

Exemplos:

- `https://api.minhakoja.com/produtos` — endpoint para acessar a coleção de produtos.
- `https://api.minhakoja.com/produtos/5` — endpoint para acessar o produto de ID `5`.

O método HTTP utilizado junto ao endpoint define a operação pretendida. Por exemplo, `GET /produtos` pode listar produtos, enquanto `POST /produtos` pode cadastrar um novo item.

## 4. 📦 JSON (JavaScript Object Notation)

**JSON** é um formato textual leve para representar e trocar dados estruturados. É amplamente utilizado na comunicação entre aplicações e APIs.

Exemplo de objeto JSON:

```json
{
  "id": 1,
  "nome": "Notebook Gamer",
  "preco": 4500.00
}
```

Os dados são organizados em pares de chave e valor. Por ser conciso e legível, o JSON é uma opção comum para respostas e solicitações de APIs.

## 5. 📝 Atividade 01

> 🚧 Os enunciados, exemplos e resultados da primeira atividade serão adicionados aqui quando estiverem disponíveis.

## 6. 🖥️ Servidor backend e Web Service

O **backend** concentra a lógica executada no servidor, como validação e processamento de solicitações, além do acesso a dados. Um **Web Service** disponibiliza funcionalidades por meio de uma interface acessível pela rede, permitindo que outros sistemas consumam seus recursos.

Em uma aplicação web, o front-end envia uma solicitação ao serviço; o backend a processa e retorna uma resposta, frequentemente em JSON.

## 7. 🚀 Criando uma API REST com Express

O **Express** é um framework para Node.js que facilita a criação de aplicações web e APIs. Com ele, é possível definir rotas associadas a métodos HTTP e implementar o comportamento de cada endpoint.

Em uma API REST, os recursos são identificados por URLs e manipulados com métodos HTTP. Por exemplo, uma rota de produtos pode oferecer operações para listar, cadastrar, atualizar e remover itens.

## 8. 🧪 Atividade 02

> 🚧 Os enunciados, o código e os resultados da atividade de criação de uma API REST com Express serão adicionados aqui quando estiverem disponíveis.

## 9. 🎨 Cascading Style Sheets (CSS)

**CSS** (Cascading Style Sheets) é a linguagem usada para definir a apresentação visual de documentos HTML. Com CSS, é possível configurar cores, tipografia, espaçamentos, dimensões e layout.

O termo *cascading* (cascata) refere-se à forma como o navegador determina quais declarações de estilo se aplicam quando há regras concorrentes. Frameworks CSS oferecem estilos e componentes reutilizáveis para agilizar a construção de interfaces.

## 10. 🔗 Projetos relacionados

Repositórios públicos relacionados aos exemplos de API e consumo de API:

- 🛠️ **API com Express:** [ronaldorfas/API-express](https://github.com/ronaldorfas/API-express)
- ⚛️ **Aplicação React com solicitação a uma API:** [ronaldorfas/Projetocom-API](https://github.com/ronaldorfas/Projetocom-API)

> ℹ️ **Observação:** o repositório da disciplina [Frameworks-Front-end](https://github.com/ronaldorfas/Frameworks-Front-end) ainda não aponta esses projetos como materiais da Aula 07. Além disso, o projeto React faz uma solicitação `POST`, enquanto o código publicado no repositório Express mostra uma rota `GET`; portanto, não confirmei que os dois formem a mesma atividade integrada.
