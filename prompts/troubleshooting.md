# Troubleshooting – Engenharia de Prompts

## ⚠️ Problemas Encontrados e Soluções

Este documento regista as principais dificuldades encontradas durante a interação com o NotebookLM e a otimização dos prompts.

---

## ❌ Problema 1: Respostas demasiado genéricas

### Descrição

As respostas iniciais da IA eram superficiais e pouco específicas.

### Causa

Prompts muito amplos e sem restrição de contexto.

### Solução

Reformular os prompts adicionando:

* "Baseado apenas nas fontes carregadas"
* Solicitação de respostas estruturadas
* Divisão por tópicos clínicos

---

## ❌ Problema 2: Falta de referências às fontes

### Descrição

As respostas não indicavam claramente de onde vinha a informação.

### Causa

Ausência de instrução explícita sobre citação de fontes.

### Solução

Adicionar ao prompt:

> "Indique a fonte utilizada em cada resposta"

---

## ❌ Problema 3: Mistura de conceitos clínicos

### Descrição

AVC isquémico e hemorrágico eram frequentemente confundidos.

### Causa

Perguntas demasiado abertas.

### Solução

Utilizar prompts comparativos estruturados:

* Tabela
* Critérios clínicos definidos
* Separação por categorias

---

## ❌ Problema 4: Falta de profundidade na reabilitação

### Descrição

Respostas sobre reabilitação eram muito superficiais.

### Causa

Falta de contexto temporal (curto, médio e longo prazo).

### Solução

Especificar no prompt:

* fases de recuperação
* objetivos por período
* intervenções detalhadas

---

## 📌 Aprendizagem Principal

A qualidade da resposta da IA depende diretamente da qualidade do prompt.

✔ Prompt claro = resposta precisa
✔ Prompt vago = resposta genérica
