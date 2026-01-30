# Context Engineering with LangChain4J Workshop

## Overview
Welcome to this hands-on workshop, where you'll learn to implement sophisticated context-engineering patterns. Context Engineering is the practice of strategically designing, structuring, and optimizing the information provided to AI models (particularly LLMs) to achieve desired outputs. It goes beyond simple prompt engineering by considering the entire context window and how data is organized, presented, and sequenced to maximize model performance. In this workshop, you will learn how to implement this using [Java](https://www.java.com/en/), [LangChain4J](https://github.com/langchain4j/langchain4j), and [Redis](https://redis.io/).

### 🎯 What you'll build

By the end of this workshop, you'll have built a complete AI application featuring:
* LLM integration using OpenAI, Spring Boot, and LangChain4J
* Vector embeddings for semantic search with a chunking strategy
* RAG (Retrieval-Augmented Generation) with knowledge bases
* Dual-layer memory architecture (short-term and long-term memory)
* Query compression techniques for efficient context retrieval
* Content Reranking to optimize relevance of retrieved information
* Few-shot learning pattern for improved generated responses
* Dynamic context window management based on token limits
* Semantic caching to optmize performance and reduce LLM costs

## 📋 Prerequisites

### Required knowledge
* Basic understanding of Java programming
* Familiarity with RESTful APIs
* Basic knowledge of LLMs and AI concepts
* Familiarity with command-line interfaces
* Basic understanding of Docker and Git

### Required software
* [Java 21+](https://www.oracle.com/java/technologies/downloads)
* [Maven 3.9+](https://maven.apache.org/install.html)
* [Docker](https://docs.docker.com/get-docker/)
* [Git](https://git-scm.com/install/)
* [Node.js](https://nodejs.org/en/download/)

### Required accounts
| Account                                                  | Description                                              |
|:---------------------------------------------------------|:---------------------------------------------------------|
| [OpenAI](https://auth.openai.com/create-account)         | LLM that will power the responses for the AI application |
| [Redis Cloud](https://redis.io/try-free)                 | Semantic caching service powered by Redis LangCache      |

## 🗺️ Workshop Structure
This workshop is organized into 9 progressive labs, each building upon the previous:

| Lab | Topic                                                           | Duration | Branch                             |
|:----|:----------------------------------------------------------------|:---------|:-----------------------------------
| 1   | Set up and deploy the AI application                            | 25 mins  | `lab-1-starter` → `lab-1-solution` |
| 2   | Enabling short-term memory with chat memory                     | 10 mins  | `lab-2-starter` → `lab-2-solution` |
| 3   | Knowledge base with embeddings, parsers, and splitters          | 10 mins  | `lab-3-starter` → `lab-3-solution` |
| 4   | Implementing basic RAG with knowledge base data                 | 20 mins  | `lab-4-starter` → `lab-4-solution` |
| 5   | Enabling on-demand context management for memories              | 10 mins  | `lab-5-starter` → `lab-5-solution` |
| 6   | Implementing query compression and context reranking            | 15 mins  | `lab-6-starter` → `lab-6-solution` |
| 7   | Implementing a few-shot into the system prompt design           | 05 mins  | `lab-7-starter` → `lab-7-solution` |
| 8   | Enabling token management to handle token limits                | 10 mins  | `lab-8-starter` → `lab-8-solution` |
| 9   | Implementing semantic caching for conversations                 | 25 mins  | `lab-9-starter` → `lab-9-solution` |

## 🚀 Getting Started

### Step 1: Clone the repository
```bash
git clone https://github.com/redis-developer/context-engineering-with-langchain4j.git
```

### Step 2: Verify your Environment
Ensure you have Java, Maven, Docker, and Git installed. You can check their versions with:
```bash
java -version
mvn -version
docker --version
git --version
```

### Step 3: Begin your First Lab
Navigate to the cloned repository and switch to the first lab's starter branch:
```bash
cd context-engineering-with-langchain4j
git checkout lab-1-starter
```

## Resources
- [Alexa Skill using Context Engineering](https://github.com/redis-developer/agent-memory-server-with-alexa-demo)

## Maintainers
**Maintainers:**
- Ricardo Ferreira — [@riferrei](https://github.com/riferrei)

## License
This project is licensed under the [MIT License](./LICENSE).