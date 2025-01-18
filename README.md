# Plano de Estudos 📚

Este plano foi elaborado para cobrir fundamentos e tópicos avançados em Cloud Computing, Desenvolvimento Backend, Arquitetura de Sistemas, Estruturas de Dados e outros domínios importantes para um engenheiro de software de alto nível. 

---

## **1. Fundamentos de Cloud Computing**
### **1.1. AWS**
- [ ] **API Gateway:**  
  - [ ] Conceitos fundamentais e casos de uso.  
  - [ ] Integração com AWS Lambda.  
  - [ ] Configuração de autenticação (AuthN/AuthZ).  
- [ ] **DynamoDB:**  
  - [ ] Strong consistency e eventual consistency.  
  - [ ] Throttling e estratégias de particionamento.  
  - [ ] Uso de TTL e índices globais/secundários.  
- [ ] **EC2 vs Fargate:**  
  - [ ] Comparação de casos de uso.  
  - [ ] Análise de custos e desempenho.  
- [ ] **IAM:**  
  - [ ] Configuração de políticas e funções.  
  - [ ] Criação e gestão de usuários.  
  - [ ] Integração com serviços para controle de acesso.  
- [ ] **ECS e EKS:**  
  - [ ] Diferenças entre ECS e EKS.  
  - [ ] Gerenciamento e configuração de clusters Kubernetes.  
- [ ] **Segurança:**  
  - [ ] AuthN e AuthZ utilizando OAuth2.  
- [ ] **Observability:**  
  - [ ] Configurar **Victoria Metrics** e **Grafana** para monitoramento.  
- [ ] **Well-Architected Framework:**  
  - [ ] Estudo dos cinco pilares: segurança, confiabilidade, custo, desempenho, excelência operacional.  
- [ ] **Landing Zones:**  
  - [ ] Estrutura, boas práticas e implementação.

---

## **2. Desenvolvimento Backend e Frameworks**
### **2.1. Java**
- [ ] **Java 21:**  
  - [ ] Explorar novas funcionalidades: padrões de correspondência, classes de dados, APIs atualizadas.  
- [ ] **Comparação de Frameworks:**  
  - [ ] Spring Boot.  
  - [ ] Quarkus.  
  - [ ] Micronaut.  
  - [ ] MicroProfile.  
- [ ] **Reactor:**  
  - [ ] Programação reativa utilizando Spring WebFlux.

### **2.2. Golang**
- [ ] **Framework GIN:**  
  - [ ] Estudo de middleware, validação e boas práticas para APIs RESTful.  

### **2.3. Estratégias de Deploy**
- [ ] **Canary Deployment:**  
  - [ ] Configuração de lançamentos graduais.  
- [ ] **Blue-Green Deployment:**  
  - [ ] Alternância de ambientes para evitar downtime.  
- [ ] **Shadow Traffic:**  
  - [ ] Roteamento de tráfego real para ambientes de teste.  

---

## **3. Arquitetura e Resiliência**
### **3.1. Arquitetura Celular**
- [ ] Conceitos e benefícios de modularidade e escalabilidade.  
- [ ] Implementação prática com microsserviços.

### **3.2. Consistência em Sistemas Distribuídos**
- [ ] Consistência eventual vs. forte.  
- [ ] Trade-offs e casos de uso.

### **3.3. Kubernetes**
- [ ] **Manifests YAML:**  
  - [ ] Criação de arquivos YAML básicos e avançados.  
- [ ] **Certificações:**  
  - [ ] Preparação para **CKA** e **CKAD**.  

### **3.4. Resiliência**
- [ ] Implementar padrões:  
  - [ ] Bulkhead.  
  - [ ] Circuit Breaker.  
  - [ ] Timeout.  
  - [ ] Retry com Jitter.  

### **3.5. Alta Performance**
- [ ] **CQRS:**  
  - [ ] Separação de leitura e escrita em bancos relacionais e não relacionais.  
- [ ] **EDA (Event-Driven Architecture):**  
  - [ ] Padrões de comunicação assíncrona e exemplos práticos.

---

## **4. Estruturas de Dados e Algoritmos**
### **4.1. Estruturas Básicas**
- [ ] **Implementação Manual:**  
  - [ ] Linked List.  
  - [ ] Hash Table.  
  - [ ] Binary Search Tree.  
  - [ ] Min-Heap.  

### **4.2. Estruturas Avançadas**
- [ ] Fenwick Tree, Interval Tree, Union-Find, Segment Tree, Skip List.

### **4.3. Prática com Algoritmos**
- [ ] Resolver pelo menos **100 problemas** no LeetCode.  

### **4.4. Domain-Driven Design (DDD)**
- [ ] Planejamento, implementação e gestão utilizando DDD.  

---

## **5. Desenvolvimento Fullstack e Arquiteturas de Frontend**
### **5.1. CSS**
- [ ] Posições (relative, absolute, fixed).  
- [ ] Media Queries.  
- [ ] OOCSS, BEM, SMACSS.  

### **5.2. Arquiteturas e Padrões**
- [ ] **MVC, MVVM, MVP, Elm Architecture, BLoC.**  
- [ ] **Atomic Design:** Componentização eficiente.  

---

## **6. Bancos de Dados e Integração**
### **6.1. NoSQL**
- [ ] Tipos: Key-Value, Column-Oriented, Document-Oriented, Graph.  
- [ ] ElasticSearch: Funcionamento interno e otimizações.

### **6.2. Padrões de Integração**
- [ ] **EIP (Enterprise Integration Patterns):** Implementação prática.  

### **6.3. Teoremas e Estratégias**
- [ ] **CAP e PIE:** Aplicação prática em sistemas distribuídos.  

---

## **7. Estratégias Avançadas de Software**
- [ ] **Serverless:**  
  - [ ] Comparação com Kubernetes e casos de uso.  
  - [ ] Implementação com AWS Lambda.  
- [ ] **Arquiteturas Lambda e Kappa:**  
  - [ ] Diferenças e aplicação prática.  
- [ ] **Event Sourcing:**  
  - [ ] Implementação com Kafka e bancos de dados.  
- [ ] **Complex Event Processing (CEP):**  
  - [ ] Construção de pipelines de eventos.  

---

## **8. Sistemas Operacionais e Gerenciamento**
- [ ] Gerenciamento de arquivos e processos no SO.  
- [ ] Diferenças entre Stack, Heap e Buffer.  
- [ ] Paginação de memória.  

---

## **9. Criptografia e Segurança**
- [ ] Criptografia simétrica e assimétrica.  
- [ ] Aplicações práticas em autenticação e bancos.  

---

## **10. Data e Analytics**
- [ ] **Data Warehousing:**  
  - [ ] Comparação entre Data Warehouse, Data Lake, Data Lakehouse.  
- [ ] **Data Mesh e Data Fabric:**  
  - [ ] Exploração e aplicações práticas.  

---

## **11. Documentação e Requisitos**
- [ ] **Design Docs:**  
  - [ ] Boas práticas para redação de documentos técnicos.  
  - [ ] Criação de requisitos claros e objetivos.  
