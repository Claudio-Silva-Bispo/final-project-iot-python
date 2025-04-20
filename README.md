# 🦷 Projeto Delfos Machine – Agendamento Inteligente de Consultas Odontológicas

## 👨‍💻 Sobre o Projeto

**Grupo:** Delfos Machine  

**Integrantes:**

- Claudio Bispo – RM553472 

- Patricia Naomi – RM552981

📽️ **Vídeo Apresentação:**  

[Assista no YouTube](https://youtu.be/WTcrkyPM7ik?si=0IGzx3giUQkyGV8i)

📁 **Repositórios:**  

- [Sprint 1 e 2](https://github.com/patinaomi/delfos-machine-1-sem.git)  

- [Sprint 3 e 4](https://github.com/patinaomi/delfos-machine-2-sem.git) -- Trocar aqui

---

## 🎯 Objetivo Geral

Desenvolver um app mobile e web para **agendamento odontológico preventivo inteligente**, que **sugere automaticamente** datas ideais para consultas com base no histórico do paciente, promovendo a saúde bucal contínua, reduzindo emergências e melhorando a eficiência para clínicas e seguradoras.

---

## 👤 Benefícios para Clientes

- 📅 **Agendamento Preventivo Automatizado** com base em perfil e histórico.

- 💸 **Redução de Custos** com procedimentos de emergência.

- 📲 **Notificações e Controle Total** sobre consultas.

- 🎁 **Programa de Benefícios:** pontos por consultas, descontos e brindes.

- 📊 **Histórico de Consultas e Recomendações Personalizadas.**

---

## 🏥 Benefícios para Clínicas

- 🧲 **Aumento da Base de Clientes** com sugestões automáticas.

- 🕒 **Redução de Horários Ociosos.**

- 🤝 **Engajamento e Fidelização de Pacientes.**

- 📆 **Gestão Inteligente da Agenda.**

- ❌ **Menor Taxa de Cancelamentos.**

---

## 🏢 Benefícios para Seguradoras Odontológicas

- 💰 **Redução de Custos com Tratamentos de Alto Custo.**

- 📉 **Menor Sinistralidade nos Planos.**

- 🤖 **Análises Inteligentes e Previsões de Risco.**

- 🌟 **Maior Satisfação dos Segurados.**

- 🧭 **Parcerias Estratégicas com Clínicas.**

---

## ⚙️ Como Funciona o Agendamento Preventivo?

1. Cliente cadastra dados e preferências de horário/local.

2. Sistema sugere automaticamente datas ideais.

3. Cliente recebe notificação e pode aceitar ou reagendar.

4. Clínica confirma a consulta.

5. Histórico do paciente é atualizado para novos ciclos.

---

## 🏆 Programa de Benefícios

### Para Clientes:

- 🔄 Pontos por consultas realizadas.

- 💳 Descontos em planos e procedimentos.

- 🎉 Brindes e experiências exclusivas.

### Para Clínicas:

- 📈 Ranking de engajamento.

- 💵 Bônus financeiros via seguradoras.

- 👨‍⚕️ Indicações automáticas de novos pacientes.

---

## 🧪 Sprint 3 – Requisitos

### ✅ Tema

Aplicativo inteligente de **agendamento preventivo odontológico** com gestão automatizada de atendimentos.

### ✅ Problema

Pacientes esquecem de marcar consultas; clínicas enfrentam horários ociosos; seguradoras têm custos altos com emergências.

### ✅ Soluções Propostas

1. Sistema de agendamento inteligente.

2. Notificações proativas.

3. Integração com seguradoras e programa de incentivos.

---

## 🧠 Tecnologias e Bibliotecas

### 🔧 **APIs e Backend**

- **Flask / FastAPI:** Criação de endpoints RESTful e API de geolocalização.

- **Oracle / MongoDB / SQL:** Para diferentes finalidades e tipos de dados.

### 📊 **Manipulação de Dados**

- **Pandas:** Processamento de histórico de pacientes e sugestões.

- **Scikit-learn:** Modelos de classificação/regressão e análise de sentimentos.

### 🤖 **IA e Machine Learning**

- **TensorFlow / Keras:** Para futuros modelos preditivos e evolução do chatbot.

---

## 🤖 Aplicações de IA/ML

### 🔮 Previsão de Consultas Preventivas

Modelos preditivos sugerem datas ideais com base no comportamento do paciente.

### 🧭 Análise de Comportamento (Clustering)

Segmentação de pacientes para ofertas e recomendações personalizadas.

### 🎯 Recomendação Inteligente

Sugestão de serviços adicionais baseados no perfil do paciente.

### ⚠️ Análise de Risco

Detecção de padrões para prever riscos de problemas bucais.

---


## 🧪 Sprint 4 – Requisitos

# 🎯 Apresentação Final do Projeto e Autocrítica

## ✅ Demonstração da Versão Final do Projeto

Nosso projeto propõe uma solução **inteligente de agendamento odontológico**, com o objetivo de otimizar a jornada do paciente e a gestão das clínicas por meio de tecnologia multiplataforma e inteligência artificial.

### 👩‍💻 Aplicações Desenvolvidas

#### 1. Aplicativo Mobile (React Native + Firebase)

- Cadastro e login com autenticação Firebase (e-mail/senha e Google)

- Área restrita com navegação por etapas para:

  - Cadastro de dados pessoais (4 sessões separadas)

  - Consulta e edição dos dados, com exclusão da conta

  - Tela de desafios e pontos, com ranking, níveis e prêmios


- Carrossel de imagens sem dependências externas

- Sistema de pontos com base nas ações realizadas pelo usuário

#### 2. Aplicação Web (ASP.NET + MongoDb)
- Interface administrativa para gerenciamento de usuários, clínicas e agendamentos

- Visualização e análise dos dados coletados pelo sistema mobile

- Suporte para relatórios e exportações

- Área segura com autenticação integrada ao Firebase

#### 3. Serviço de Backend Inteligente (Python + IA)

- Leitura automatizada dos **feedbacks** enviados pelos usuários

- **Análise de sentimentos** para ajustar notas subjetivas com base no conteúdo textual

- Classificação automática dos feedbacks em categorias e notas

- **Roteirização geográfica** entre endereço do cliente e clínicas disponíveis, determinando a unidade mais próxima

- **Rankeamento das clínicas** com base em:

  - Qualidade percebida nos feedbacks

  - Distância média dos usuários

  - Tempo de resposta e engajamento

- Integração com **ChatGPT (API OpenAI)** para:

  - Analisar os dados da base de dados completa
  
  - Gerar recomendações automáticas para **consultas preventivas futuras** através da última tabela que é o resultado da consulta, onde o dentista informa tudo que foi realizado e através do texto, conseguimos mapear os próximos agendamentos.

  - Auxiliar o usuário com **orientações personalizadas após as consultas** e notificações para não perder nenhuma etapa.

---

## 🧠 Autocrítica: Reflexões Sobre o Processo

### O que funcionou bem

No início, a separação entre os pedidos e as entregas dificultou as integrações, pois havia várias camadas nas quais gostaríamos de atuar. No entanto, a integração entre o front-end e o back-end não era simples. Ainda assim, conseguimos superar esses desafios e aplicar as soluções de forma eficaz.

- Integração eficaz entre o front-end mobile e web com o backend Firebase, MongoDb e Python. Foi necessário criar uma única fonte de dados através do Python para que pudessemos utilizar as informações de forma mais simples e tratar os dados em um único lugar.

- Cadastro modular e claro com excelente UX

- Carregamento progressivo dos dados por sessão e tratamento em camadas/etapas.

- Sistema de gamificação pode aumentar o engajamento do usuário

- Leitura de feedbacks com NLP usando Python apresentou resultados promissores

- A estrutura do backend foi projetada de forma a permitir escalabilidade

- Utilizando bibliotecas do Python como Pandas, Scikit-learn, PyTorch e outras para integração com bancos de dados, conseguimos realizar o CRUD após o tratamento dos dados. Isso permitiu que as informações fizessem sentido e nos possibilitou entregar uma solução funcional e inteligente.

### O que não funcionou bem ou foi desafiador

- A **integração entre múltiplas tecnologias** exigiu muito controle de autenticação e segurança entre camadas muito delicada

- **Sincronização de dados entre Firebase e backend Python** exigiu estrutura adicional para não gerar conflitos ou redundância

- Alguns **feedbacks subjetivos não eram interpretáveis** por IA sem contexto, o que exigiu tratamento especial

- **Roteirização por endereço real** dependia de APIs externas com limites de uso gratuito

- A comunicação entre **ChatGPT e o banco de dados** exigiu cuidados com formatação e validação de dados

- **Ausência de testes automatizados** dificultou a validação rápida de atualizações

- Interface web inicial estava com visual ainda genérico e muito simples

---

## 🔁 O que faríamos diferente

- Implementar **camada unificada de autenticação**

- Usar **Zustand ou Redux** no React Native

- Criar **microserviços Python** para IA e roteirização

- Automatizar testes no front e backend

- Criar painel analítico mais robusto no ASP.NET

- Utilizar um único banco de dados para utilização da informação de forma mais simples e rápida.

---

## 🚀 Planos Futuros para Expansão ou Melhoria

- 📌 **Painel de Controle da Clínica** com insights em tempo real

- 💡 **Sistema de Recomendação Avançado com IA**

- 📱 **Notificações inteligentes personalizadas**

- 🌍 **Integração com APIs públicas de saúde**

- 🧠 **Treinamento de modelos próprios de ML**

- 🧾 **Automatização com OCR**

- 🛡️ **Aderência à LGPD**

- 🔄 **Sistema de fila inteligente para agendamentos** -- Ponto que foi discutido com a matéria de Java e que fez muito sentido


## ✅ Conclusão

Nosso app vai **além do agendamento tradicional**: ele é um **sistema inteligente e preventivo** para saúde bucal, promovendo um ecossistema de ganhos mútuos:

**+ Pacientes engajados**  

**+ Clínicas com agenda cheia**  

**+ Seguradoras com menos emergências**  

= **🚀 Revolução na Odontologia Preventiva**