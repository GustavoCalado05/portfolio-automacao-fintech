# 🚀 Portfólio de Automação & Backend (Fintech Focus)

Bem-vindo ao meu repositório de projetos práticos. Este portfólio demonstra minhas competências em **Lógica de Programação**, **Integração de Sistemas** e **Automação de Processos (Low-Code)** aplicados a cenários reais do mercado financeiro.

O objetivo destes fluxos é apresentar soluções escaláveis para problemas comuns de triagem de dados, validação cadastral e monitoramento financeiro.

## 🛠️ Tecnologias Utilizadas
* **n8n (Workflow Automation):** Orquestração de fluxos e rotinas de backend.
* **JavaScript (ES6):** Scripting avançado para manipulação de dados e regras de negócio complexas.
* **APIs REST:** Consumo e integração com serviços externos (HTTP Request).
* **JSON:** Estruturação e padronização de troca de dados.
* **Lógica de Dados:** Condicionais (If/Switch), transformação e roteamento.

---

## 📂 Projetos Disponíveis

### 1. [Lógica] Teste de condicional (`Teste_de_condicional.json`)
Simulação de um backend utilizando condicioanal IF via **Webhook**, aplica regras de negócio para categorizar clientes (VIP vs. Varejo) com base no volume financeiro e direciona os dados para o banco de dados correto (SQL) ou para arquivamento.
* **Competências:** Webhooks, Roteamento de Dados, Estrutura de Decisão.

### 2. [Scripting] Validador de CPF via Código (`validar_cpf.json`)
Módulo de validação cadastral que utiliza o **Node Code** do n8n. Em vez de depender de componentes prontos, desenvolvi um script em **JavaScript** que recebe o input, verifica a integridade do dado (quantidade de dígitos e formatação) e retorna o status de validade para o fluxo.
* **Competências:** JavaScript, Manipulação de Strings, Lógica de Programação.

### 3. [Integração] Monitor de Cotação em Tempo Real (`monitor_cotacao.json`)
Automação que consome uma **API Pública de Câmbio** (AwesomeAPI) para monitorar a cotação do Dólar (USD/BRL) em tempo real. O fluxo possui gatilhos condicionais que disparam alertas automáticos caso a moeda ultrapasse um teto pré-definido (regra de Compliance/Tesouraria).
* **Competências:** HTTP Request (GET), Consumo de API, Tratamento de JSON, Monitoramento.

---

## ⚙️ Como executar os projetos
Para visualizar e testar os fluxos na sua máquina:

1.  Tenha o **n8n** instalado (ou utilize a versão Cloud).
2.  Baixe o arquivo `.json` do projeto desejado neste repositório.
3.  No n8n, vá em **Workflow** > **Import from File**.
4.  Selecione o arquivo e o fluxo será carregado com todas as configurações.

---
*Desenvolvido por Gustavo Soares - Focado em Soluções de Tecnologia e Negócios.*
