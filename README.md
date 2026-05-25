# 💡 Sistema de Iluminação Inteligente com Arduino e Arquitetura ARM

Este projeto consiste no desenvolvimento de um **Sistema de Iluminação Inteligente** utilizando a plataforma :contentReference[oaicite:0]{index=0}, programação em linguagem C/C++ e simulação em arquitetura ARM.  
O sistema realiza a automação do acionamento da iluminação com base em dados de sensores, aplicando conceitos introdutórios de Inteligência Artificial por meio de regras de tomada de decisão.

---

## 📌 Objetivo do Projeto

Desenvolver um sistema embarcado capaz de:
- Monitorar a luminosidade do ambiente;
- Detectar a presença de pessoas;
- Tomar decisões automáticas;
- Acionar ou desligar a iluminação de forma inteligente.

---

## 🧠 Conceitos Aplicados

- Sistemas embarcados
- Arquitetura ARM
- Programação em C/C++
- Sensores e atuadores
- Inteligência Artificial baseada em regras
- Automação
- Versionamento com GitHub

---

## ⚙️ Funcionamento do Sistema

O sistema analisa continuamente os dados dos sensores e executa a seguinte lógica:

- Se o ambiente estiver **escuro** e houver **presença**, a iluminação é **ligada**;
- Se o ambiente estiver **claro** ou **sem presença**, a iluminação é **desligada**.

Essa lógica representa um algoritmo simples de tomada de decisão inteligente.

---

## 🧰 Componentes Utilizados

### Hardware
- Arduino (Uno, Mega ou similar)
- Sensor LDR (luminosidade)
- Sensor PIR (presença)
- LED ou módulo relé
- Resistores
- Protoboard
- Jumpers

### Software
- Arduino IDE
- Linguagem C/C++
- Simulador de arquitetura ARM
- GitHub

---

## 🧪 Simulação em Arquitetura ARM

Antes da implementação física, o algoritmo foi testado em um ambiente de simulação compatível com arquitetura ARM, garantindo:
- Validação da lógica de decisão;
- Redução de erros;
- Melhor confiabilidade do sistema final.

---

## 📂 Estrutura do Repositório
