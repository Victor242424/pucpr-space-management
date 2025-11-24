# **Case Técnico – Processo Seletivo**

## **Estrutura do Projeto**

Este projeto está dividido em duas partes principais:

### **📂 Backend** (`/backend`)
- API REST desenvolvida em **Java 21 com Spring Boot**
- Documentação completa disponível em [`backend/README.md`](backend/README.md)
- Configuração Docker em arquivos `docker-compose` separados por responsabilidade
- Banco de dados PostgreSQL com gerenciamento de persistência

### **📂 Frontend** (`/frontend`)
- Aplicação web desenvolvida em **Angular 21**
- Documentação completa disponível em [`frontend/README.md`](frontend/README.md)
- Configuração Docker própria com Nginx
- Interface responsiva com Tailwind CSS

**Cada pasta contém:**
- README.md específico com instruções detalhadas de instalação e execução
- Arquivos docker-compose próprios para deployment
- Configurações e dependências independentes

Para instruções completas de configuração, instalação e execução de cada módulo, consulte os READMEs específicos em suas respectivas pastas.

---

## **Problema**

Desenvolver uma aplicação web para **controlar o uso de espaços de ensino**, permitindo análise da taxa de ocupação.  
Um ambiente de ensino pode ser uma **sala de aula**, **laboratório** ou **sala de estudos**.  
A aplicação deve possibilitar o **cadastro de alunos**, que deverão **registrar presença ao entrar e sair do ambiente**.  
A especificidade do projeto (detalhes adicionais, regras de negócio) fica a critério do candidato.

***

## **Pré-requisitos**

*   **Não existe sistema atual na instituição** que forneça estrutura inicial.
*   **Back-end**: Java (Spring) **ou** Node.js.
*   **Front-end**: React **ou** Angular.
*   **Armazenamento**: Implementar **um mecanismo de persistência de dados** (tipo de banco ou tecnologia a critério do candidato).
*   **Funcionalidades obrigatórias**:
    *   CRUD para cadastro de alunos.
    *   Registro de entrada e saída dos ambientes de ensino.
*   **API**:
    *   Deve existir uma API para comunicação entre front-end e back-end.
    *   **A API deve implementar autenticação via token e garantir autorização adequada para que apenas usuários autenticados possam acessar e executar operações permitidas.**

***

## **Critérios de Avaliação**

*   Organização e clareza do código.
*   Uso de boas práticas (estrutura, padrões, segurança).
*   Documentação mínima para execução do projeto.
*   Qualidade da solução proposta (funcionalidade, usabilidade).
*   Criatividade na definição das regras de negócio.

***

## **Como Participar**

1.  **Faça um fork deste repositório.**
2.  Desenvolva sua solução no repositório criado pelo fork.
3.  Certifique-se de que o repositório esteja **público**.
4.  O **último commit** deve ser realizado até **24/11/2025 às 08:00**.
5.  Envie a URL do seu repositório para o e-mail ana.neneve@pucpr.br até o mesmo prazo do commit.
