Claro! Aqui está o texto reescrito em **formato clean** e **sem firulas**, pronto para copiar e colar diretamente em apresentações, relatórios ou outros documentos:

---

## 📊 Análise de Evasão de Clientes (Churn Prediction)

### 🎯 Objetivo do Projeto

Identificar os principais fatores que levam à evasão de clientes em uma empresa de telecomunicações, utilizando técnicas de machine learning para prever o churn e propor ações práticas de retenção.

---

### 💡 Objetivos Específicos

* Analisar o perfil dos clientes e identificar padrões de evasão.
* Aplicar modelos de machine learning para prever a saída de clientes.
* Comparar modelos com e sem normalização.
* Utilizar o SMOTE para balancear as classes e melhorar a equidade.
* Gerar insights acionáveis para retenção de clientes.

---

### 🧠 Modelos Utilizados

**1. Regressão Logística com SMOTE**

* Exige normalização dos dados.
* Fornece boa interpretabilidade por meio dos coeficientes.
* Principais variáveis: Encargos\_Mensais, Encargos\_Totais, Tempo\_Servico.

**2. Random Forest com SMOTE**

* Não exige normalização.
* Capta relações complexas entre variáveis.
* Principais variáveis: Tempo\_Servico, Encargos\_Totais, Contrato\_Conta.

---

### 🔎 Principais Insights

**Fatores que aumentam a evasão:**

* Altos encargos mensais e totais.
* Contrato mensal.
* Uso de internet por fibra óptica.
* Baixo tempo de serviço.

**Fatores que reduzem a evasão:**

* Clientes com mais tempo de vínculo.
* Contrato bienal.
* Presença de dependentes ou parceiro cadastrado.

---

### 🛠️ Técnicas Utilizadas

* Pré-processamento (encoding, normalização).
* Balanceamento de classes com SMOTE.
* Ajuste de hiperparâmetros com GridSearchCV.
* Avaliação com Acurácia, Precisão, Recall, F1-score e Matriz de Confusão.
* Análise interpretativa dos coeficientes e importâncias.

---

### 📈 Avaliação dos Modelos

| Modelo                      | Acurácia | Precisão | Recall | F1-score |
| --------------------------- | -------- | -------- | ------ | -------- |
| Regressão Logística (SMOTE) | 0.7611   | 0.5287   | 0.6578 | 0.5862   |
| Random Forest (SMOTE)       | 0.7652   | 0.5375   | 0.6257 | 0.5783   |

* A regressão logística teve melhor recall.
* A Random Forest apresentou maior estabilidade geral.

---

### 📌 Conclusão

A evasão de clientes está relacionada a padrões claros de comportamento e percepção de valor. Os modelos aplicados demonstraram que é possível antecipar o churn e propor ações de retenção mais eficazes e personalizadas. Com esses insights, a empresa pode transformar riscos de saída em oportunidades de reconexão com seus clientes.

---
