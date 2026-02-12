# Agile Project Management Platform 🚀

Solução para **gestão, acompanhamento e visibilidade de times de desenvolvimento ágeis**, com foco em transparência, comprometimento e tomada de decisão baseada em dados reais.

---

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo **apoiar times que adotam metodologias ágeis** no planejamento, organização e acompanhamento do desenvolvimento de software.

A solução busca oferecer **maior visibilidade sobre a evolução dos incrementos**, facilitando o acompanhamento do progresso das demandas entre uma *daily* e outra, bem como a identificação de gargalos, impactos e travamentos no fluxo de trabalho.

---

## 🧠 Contexto e Origem da Iniciativa

A iniciativa surgiu a partir de um processo utilizado pelos times de **Talent Acquisition**, envolvendo os produtos:

- Portal de Talentos  
- Gestão de Recrutamento e Seleção  
- Admissão Digital  

da linha de produto **HCM**, da **Senior Sistemas S/A**.

Nesse contexto, observou-se a necessidade de melhorar a forma como é gerado e comunicado o **comprometimento dos desenvolvedores em relação às atividades da Sprint até a próxima daily**.

Em vez do modelo tradicional onde o desenvolvedor relata:
- O que fez
- O que pretende fazer
- Se possui impedimentos  

o processo passou a focar em **qual status a atividade deverá alcançar até a próxima daily**.

---

## 🔄 Modelo de Comprometimento por Status

Os desenvolvedores sinalizam explicitamente o estado desejado da atividade até a próxima daily, utilizando os seguintes status:

- **Avaliar e planejar**  
  Indica que ainda existem análises, impactos ou definições pendentes.

- **Enviar atividade para Code Review**  
  Indica a intenção de concluir a etapa de desenvolvimento (codificação).

- **Enviar atividade para Review**  
  Indica que o *code review* será finalizado e a demanda seguirá para testes.  
  *(Exclusivo para bugs e stories)*

- **Finalizar**  
  Indica que a demanda será concluída, com **deploy realizado**, até a próxima daily.

---

## ⚠️ Problema Atual

Atualmente, o controle desse avanço é realizado **de forma manual**, através da criação de listas em blocos de notas que posteriormente são compartilhadas no chat do time.

Essa prática apresenta diversas limitações:

- ❌ Baixa visibilidade sobre impactos reais e travamentos
- ❌ Dificuldade em acompanhar a evolução histórica das demandas
- ❌ Ausência de dados consolidados para análise por Squad Leaders e coordenadores
- ❌ Processo altamente manual e sujeito a erros

A seguir é apresentado um exemplo de como é realizada a lista de compromentimento das atividades atualmente:

## 📌 Lista de Comprometimento — Daily

**Data:** 09/02/2026  
**Desenvolvedor:** Fulano da Silva

---

### 📝 Atividades

- **HCMXXX-99999** — Finalizar  
- **HCMXXX-99998** — Enviar para *Ready To Deploy* _(7)_  
- **HCMXXX-99997** — Avaliar e Planejar _(12)_  
- **HCMXXX-99996** — Avaliar e Planejar  
- **HCMXXX-99995** — Enviar para Review  
- **HCMXXX-99994** — Finalizar _(2)_  
- **HCMXXX-99993** — Finalizar  
- **HCMXXX-99992** — Avaliar e Planejar _(4)_  
- **HCMXXX-99991** — Avaliar e Planejar _(2)_  
- **HCMXXX-99990** — Finalizar  
- **HCMXXX-99989** — Enviar para Code Review  
- **HCMXXX-99988** — Enviar para CR _(2)_  
- **HCMXXX-99987** — Enviar para CR _(3)_  
- **HCMXXX-99986** — Finalizar _(5)_  
- **HCMXXX-99985** — Avaliar e Planejar _(2)_  
- **HCMXXX-99984** — Finalizar  
- **HCMXXX-99983** — Enviar para Code Review  
- **HCMXXX-99982** — Enviar para Code Review  

---

## 🚀 Proposta da Solução

O desenvolvimento deste projeto consiste em:

- Automatizar o controle do avanço das demandas
- Centralizar o acompanhamento por tarefa, membro e tipo de atividade
- Possibilitar análises históricas por:
  - Tarefa
  - Desenvolvedor
  - Tipo de demanda
  - Data / daily
- Aumentar a transparência e previsibilidade do fluxo de trabalho
- Apoiar líderes técnicos e gestores na tomada de decisão

---

## 🏗️ Arquitetura e Especificação

A especificação arquitetural da solução foi modelada no Miro:

🔗 **Miro – Arquitetura da Solução**  
https://miro.com/app/board/uXjVGD9BAvg=/

---

## 🧩 Repositórios do Projeto

### 🎨 Frontend
Aplicação responsável pela visualização, interação e acompanhamento das demandas.

🔗 https://github.com/agile-project-management-platform/agile-management-platform-frontend

---

### ⚙️ Backend
API responsável pela gestão das demandas, status, histórico e regras de negócio.

🔗 https://github.com/agile-project-management-platform/agile-management-platform-backend

---

## 📈 Benefícios Esperados

- Maior clareza sobre o comprometimento real do time
- Redução de ruído nas dailies
- Histórico confiável para análise e melhoria contínua
- Apoio direto à liderança técnica e gestão de squads
- Evolução do processo ágil baseada em dados, não apenas percepção

---

## 📄 Licença

N/A
