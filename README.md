# 📘 Desnormalização: Estratégia de Otimização da Performance de Banco de Dados

---

## 📌 Contexto e Objetivos

Este repositório foi desenvolvido com o objetivo de estudar e consolidar o conhecimento sobre desnormalização, uma estratégia utilizada para otimização de performance em bancos de dados.

O principal intuito deste material é apoiar os estudos para a prova da faculdade, ao mesmo tempo em que aprofunda a compreensão teórica e prática sobre o tema.

### 🎯 Objetivos específicos:
- Compreender o conceito de desnormalização e sua finalidade  
- Identificar cenários onde sua aplicação é recomendada  
- Analisar vantagens e desvantagens dessa abordagem  
- Entender o impacto na performance de consultas  
- Aplicar o conceito em exemplos práticos  
- Reforçar o aprendizado para avaliação acadêmica  

---

## 📚 Curadoria de Fontes

### 📄 Material de Aula – Performance de Banco de Dados (PostgreSQL)

Conteúdo principal utilizado no estudo, abordando conceitos fundamentais de performance, otimização e análise de consultas.

**Principais tópicos:**
- Conceito de performance  
- Fatores que afetam o desempenho  
- Uso de índices  
- Normalização vs desnormalização  
- Ferramentas de análise como EXPLAIN e ANALYZE  

> “Normalizar mantém integridade e evita redundância; desnormalizar pode melhorar velocidade em cenários de leitura intensa.”

---

### 📄 PostgreSQL – Conceitos e Ferramentas

Base prática para análise de performance em banco de dados.

**Contribuições:**
- Tipos de índices (B-Tree, Hash, GIN, GiST, BRIN)  
- Ferramentas de diagnóstico:
  - EXPLAIN  
  - EXPLAIN ANALYZE  
  - pg_stat_statements  

---

### 📄 Conceitos de Otimização de Consultas SQL

Aplicação prática de performance em consultas.

**Pontos abordados:**
- Escrita eficiente de queries  
- Diferença entre Seq Scan e Index Scan  
- Redução de custo de execução  
- Impacto da estrutura das tabelas  

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Durante o estudo, foram realizados testes com diferentes prompts para obter respostas mais completas e úteis.

### 🔍 Prompts Utilizados e Evolução

**Prompt 1:**
> O que é desnormalização?

➡️ Resposta superficial  

**Refinamento:**
> Explique o que é desnormalização em banco de dados e quando ela deve ser utilizada  

---

**Prompt 2:**
> Qual a diferença entre normalização e desnormalização?

➡️ Resposta básica  

**Refinamento:**
> Explique a diferença com exemplos práticos e impacto na performance  

---

**Prompt 3:**
> Como melhorar a performance do banco?

➡️ Muito genérico  

**Refinamento:**
> Quais estratégias de otimização no PostgreSQL envolvem desnormalização, índices e análise de consultas?  

---

**Prompt 4:**
> O que é EXPLAIN?

➡️ Definição simples  

**Refinamento:**
> Explique EXPLAIN e EXPLAIN ANALYZE e como ajudam na performance  

---

### ⚠️ Cicatrizes (Dificuldades)

- Respostas genéricas no início  
- Falta de exemplos práticos  
- Necessidade de refinar várias vezes  
- Dificuldade em conectar teoria com prática  

---

### 💡 Aprendizados

- Prompts específicos geram respostas melhores  
- Contexto (ex: PostgreSQL) faz diferença  
- Pedir exemplos melhora o entendimento  
- Iteração é essencial  

---

### 🧠 Prompt Final Ideal

> Explique desnormalização em banco de dados, incluindo definição, vantagens, desvantagens, exemplos práticos e impacto na performance no PostgreSQL

---

## 📖 Miniguia de Estudo

### 📝 Resumo Estruturado

**O que é desnormalização?**  
É o processo de adicionar redundância ao banco de dados com o objetivo de melhorar a performance de consultas.

**Para que serve?**
- Reduzir a necessidade de JOINs  
- Melhorar velocidade de leitura  
- Otimizar consultas frequentes  

**Quando usar?**
- Sistemas com muitas consultas (leitura intensa)  
- Relatórios e dashboards  
- Grandes volumes de dados  

**Vantagens:**
- Melhor performance  
- Consultas mais rápidas  
- Menor complexidade em algumas queries  

**Desvantagens:**
- Redundância de dados  
- Maior risco de inconsistência  
- Mais difícil de manter  

---

### 📚 Glossário

| Termo | Definição |
|------|----------|
| Desnormalização | Adição de redundância para melhorar performance |
| Normalização | Organização dos dados para evitar redundância |
| Índice | Estrutura que acelera buscas |
| Seq Scan | Varredura completa da tabela |
| Index Scan | Busca utilizando índice |
| EXPLAIN | Mostra plano de execução |
| EXPLAIN ANALYZE | Mostra execução real |
| Query | Consulta SQL |

---

### 🤖 Prompts Reutilizáveis

- Explique desnormalização de forma simples  
- Quando usar desnormalização?  
- Quais os impactos na performance?  
- Explique EXPLAIN ANALYZE com exemplo  
- Quais os erros mais comuns em otimização de banco?  

---

## 🚀 Conclusão

Este estudo permitiu compreender não apenas o conceito de desnormalização, mas também sua aplicação prática no contexto de performance de banco de dados.

Além disso, o uso de ferramentas de IA contribuiu para o desenvolvimento de habilidades importantes como:
- Engenharia de prompts  
- Pensamento analítico  
- Interpretação de resultados  

---

## 📌 Autor

Desenvolvido por **Erik Lins**  
