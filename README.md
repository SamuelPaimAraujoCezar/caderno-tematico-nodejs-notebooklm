# Caderno Temático - Assincronismo em Node.js

## 📚 Contexto e Objetivos

Este projeto foi desenvolvido como parte do desafio da DIO utilizando o NotebookLM como ferramenta de aprendizagem ativa.

### Tema Escolhido

Assincronismo em Node.js: Callbacks, Promises e Async/Await.

### Objetivos de Estudo

- Compreender o modelo assíncrono do Node.js.
- Entender o funcionamento do Event Loop.
- Aprender a utilizar Callbacks.
- Conhecer Promises e seus benefícios.
- Aplicar Async/Await em situações reais.
- Construir uma base sólida para desenvolvimento backend com Node.js.

---

## 🔎 Curadoria de Fontes

As seguintes fontes foram utilizadas no NotebookLM para construção do caderno temático:

1. Node.js - Overview of Blocking vs Non-Blocking
   https://nodejs.org/en/learn/asynchronous-work/overview-of-blocking-vs-non-blocking

2. Node.js - Event Loop
   https://nodejs.org/en/learn/asynchronous-work/event-loop-timers-and-nexttick

3. MDN - Promise
   https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

4. MDN - Async Function
   https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function

5. JavaScript.info - Promises
   https://javascript.info/promise-basics

---

## 🤖 Engenharia de Prompts

### Prompt 1

**Pergunta:**

> Explique o que é programação assíncrona em Node.js para um desenvolvedor iniciante.

**Principais aprendizados:**

- Node.js trabalha com operações bloqueantes e não bloqueantes.
- Operações de I/O são executadas de forma assíncrona.
- O Event Loop coordena a execução das tarefas.
- Async/Await é a forma moderna de lidar com assincronismo.

---

### Prompt 2

**Pergunta:**

> Qual é a função do Event Loop no Node.js? Explique passo a passo.

**Principais aprendizados:**

- O Event Loop é o mecanismo central do Node.js.
- Permite que uma única thread execute múltiplas operações.
- Possui fases como Timers, Poll, Check e Close Callbacks.
- Processa callbacks, Promises e process.nextTick().

---

### Prompt 3

**Pergunta:**

> Compare Callbacks, Promises e Async/Await apresentando vantagens e desvantagens.

**Principais aprendizados:**

| Recurso | Vantagem | Desvantagem |
|----------|----------|-------------|
| Callback | Simples e nativo | Callback Hell |
| Promise | Melhor organização | Curva de aprendizado |
| Async/Await | Código limpo e legível | Pode gerar execução sequencial desnecessária |

---

### Prompt 4

**Pergunta:**

> Mostre exemplos práticos de uso de Async/Await em APIs Node.js.

**Principais aprendizados:**

- Uso de try/catch para tratamento de erros.
- Melhor legibilidade do código.
- Uso de Promise.all() para execução concorrente.
- Código semelhante ao fluxo síncrono tradicional.

---

## ⚠️ Cicatrizes e Troubleshooting

Durante os testes no NotebookLM, alguns desafios foram encontrados.

### Dificuldade 1

As primeiras respostas sobre Event Loop eram muito técnicas e difíceis de entender.

### Solução

Reformular o prompt adicionando:

> Explique passo a passo para um desenvolvedor iniciante.

### Resultado

A resposta ficou mais didática e fácil de compreender.

---

### Dificuldade 2

As respostas sobre Async/Await explicavam apenas a sintaxe.

### Solução

Solicitar exemplos reais:

> Mostre exemplos práticos de uso de Async/Await em APIs Node.js.

### Resultado

Foram apresentados exemplos próximos de situações encontradas em aplicações backend.

---

### Aprendizado

Pequenas mudanças nos prompts geram respostas significativamente melhores, evidenciando a importância da engenharia de prompts.

---

## 📖 Miniguia de Estudos

### O que é Programação Assíncrona?

Modelo que permite ao Node.js continuar executando outras tarefas enquanto aguarda operações de I/O.

### O que é o Event Loop?

Mecanismo responsável por coordenar a execução de tarefas assíncronas no Node.js.

### O que são Callbacks?

Funções executadas após a conclusão de uma operação assíncrona.

### O que são Promises?

Objetos que representam o resultado futuro de uma operação assíncrona.

Estados possíveis:

- Pending
- Fulfilled
- Rejected

### O que é Async/Await?

Sintaxe moderna baseada em Promises que torna o código assíncrono mais legível.

### Boas Práticas

- Preferir Async/Await em novos projetos.
- Utilizar try/catch para tratamento de erros.
- Utilizar Promise.all() para tarefas independentes.
- Evitar Callback Hell.

---

## 📘 Glossário

### Assincronismo

Execução de tarefas sem bloquear o restante da aplicação.

### Event Loop

Mecanismo que gerencia eventos e callbacks no Node.js.

### Callback

Função executada após a conclusão de uma operação.

### Promise

Objeto que representa sucesso ou falha futura de uma operação.

### Async

Palavra-chave que define uma função assíncrona.

### Await

Palavra-chave utilizada para aguardar a resolução de uma Promise.

### I/O

Operações de entrada e saída, como leitura de arquivos ou comunicação com bancos de dados.

### Promise.all()

Método utilizado para executar múltiplas Promises simultaneamente.

---

## 🚀 Prompts Reutilizáveis

- Explique [conceito] para um desenvolvedor iniciante.
- Mostre exemplos práticos de [conceito] utilizando Node.js.
- Compare [conceito A] e [conceito B].
- Quais erros comuns iniciantes cometem em [conceito]?
- Como esse conceito é utilizado em aplicações reais?
- Crie exercícios para praticar [conceito].

---

## 🎯 Conclusão

O uso do NotebookLM permitiu consolidar conhecimentos sobre assincronismo em Node.js através da análise de múltiplas fontes, da experimentação de diferentes estratégias de prompts e da construção de um material estruturado para futuras revisões.

O estudo demonstrou a importância do Event Loop, das Promises e do Async/Await para o desenvolvimento de aplicações escaláveis e eficientes utilizando Node.js.
