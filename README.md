# Apache Spark Essentials 🚀

> "Isso não é um curso zero to hero. Já adianto que você não vai sair daqui um mestre do Spark. Mas pelo menos vai entender o básico para conseguir se virar no mercado de trabalho e enfrentar desafios do cotidiano."

## 📚 Sumário

- [O que é o Apache Spark](#o-que-é-o-apache-spark)
- [Arquitetura do Spark](#arquitetura-do-spark)
  - [Processamento distribuído e Clusters](#processamento-distribuído-e-clusters)
  - [Driver? Worker? É de comer?](#driver-worker-é-de-comer)
  - [Transformações e Ações](#transformações-e-ações)
    - [O que significa "Lazy Evaluation"](#o-que-significa-lazy-evaluation)
    - [Qual a diferença entre uma Transformação e uma Ação?"](#qual-a-diferença-entre-uma-transformação-e-uma-ação) 
    - [O que seriam Narrow e Wide](#o-que-seriam-narrow-e-wide)
- [Subindo um cluster Spark](#subindo-um-cluster-spark)
  - [Instalando o Docker e Docker Compose](#instalando-o-docker-e-docker-compose)
  - [Instanciando um Jupyter Notebook](#instanciando-um-jupyter-notebook)
    - [Jupyter vs Spark Submit](#jupyter-vs-spark-submit)
- [Utilizando as funções do Spark](#utilizando-as-funções-do-spark)
- [UDFs](#udfs)
  - [O que são](#o-que-são)
  - [Quando utilizar](#quando-utilizar)
- [Spark Streaming](#spark-streaming)
  - [O que é](#o-que-é)
  - [Exemplos de uso](#exemplos-de-uso)
- [Boas práticas](#boas-práticas)
  - [O que é shuffling e como evitar](#o-que-é-shuffling-e-como-evitar)
  - [Small file problem e Skewed Partitions](#small-file-problem-e-skewed-partitions)
  - [Táticas de joining (broadcast, bucket)](#táticas-de-joining-broadcast-bucket)
  - [Analisando execution plans](#analisando-execution-plans)

---

## 🧐 O que é o Apache Spark

(Explicação introdutória sobre o Spark, destacando que é uma engine de processamento distribuído de dados)

## ⚙️ Arquitetura do Spark

### 🔥 Processamento distribuído e Clusters
(Explicação sobre a estrutura de clusters no Spark)

### 🤖 Driver? Worker? É de comer?
(Detalhes sobre os papéis do Driver e dos Workers)

### 🔄 Transformações e Ações

#### 🥱 O que significa "Lazy Evaluation"
(Explicação sobre lazy evoluation no Spark)

#### 🧮 Qual a diferença entre uma Transformação e uma Ação?
(Explicação sobre a diferença entre esses conceitos e por que é tão importante)

#### 🛤️ O que seriam Narrow e Wide
(Explicação sobre tipos de transformações e impacto na performance)

## 🚀 Subindo um cluster Spark

### 🐳 Instalando o Docker e Docker Compose
(Guia passo a passo para configurar um ambiente com Docker)

### 📒 Instanciando um Jupyter Notebook
(Como rodar o Spark dentro do Jupyter)

#### 🔄 Jupyter vs Spark Submit
(Comparação entre os dois métodos de execução de código no Spark)

## 🛠️ Utilizando as funções do Spark

Principais funções utilizadas no Spark:

- **Manipulação de colunas**:
  - `select()`
  - `withColumn()` / `withColumnRenamed()`
  - `drop()`
  - `alias()`

- **Filtragem e agregação**:
  - `filter()` / `where()`
  - `distinct()`
  - `groupBy()` + `agg()`
  - `count()`, `sum()`, `avg()`, `min()`, `max()`

- **Ordenação e limites**:
  - `orderBy()`
  - `limit()`

- **Joins e combinações**:
  - `join()`
  - `union()`

- **Transformações complexas**:
  - `explode()`
  - `collect_list()` / `collect_set()`
  - `pivot()`

## 🧑‍💻 UDFs (User Defined Functions)

### 🔬 O que são
(Explicação sobre funções definidas pelo usuário para personalizar processamento de dados)

### ⏳ Quando utilizar
(Casos em que as UDFs são úteis e quando evitá-las para manter a performance)

## 📡 Spark Streaming

### 📊 O que é
(Explicação sobre o processamento de dados em tempo real no Spark)

### ⚡ Exemplos de uso
(Casos de uso comuns como ingestão de logs, processamento de eventos em tempo real, etc.)

## ✅ Boas práticas

### ⚠️ O que é shuffling e como evitar
(Explicação sobre shuffling e estratégias para minimizar seu impacto)

### 🗂️ Small file problem e Skewed Partitions
(Explicação sobre pequenos arquivos e partições desbalanceadas, além de estratégias para lidar com isso)

### 🔀 Táticas de joining (broadcast, bucket)
(Explicação sobre diferentes estratégias de join para otimizar performance)

### 📊 Analisando execution plans
(Como interpretar o plano de execução do Spark para otimizar queries)

---

## 📢 Contribuindo

Fique à vontade para contribuir com melhorias, sugestões ou correções! Basta abrir um PR ou criar uma issue no repositório. 🚀

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

💡 **Dica:** Se você gostou desse conteúdo, não se esqueça de dar uma ⭐ no repositório!
