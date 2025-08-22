# Case-T-cnico-Vaga-Data-Scientist-An-lise-de-Regress-o
O estudo teve como objetivo analisar se a política interna de uma empresa farmacêutica, que busca não discriminar salários por localização geográfica, está sendo efetivamente cumprida.
Perfeito! Extraí o conteúdo do seu notebook e já identifiquei que ele trata de um **case técnico para vaga de Data Scientist**, com análise de regressão sobre salários de funcionários de uma empresa farmacêutica.

Aqui está um modelo de **README.md** para o GitHub, destacando os principais insights:

---

# 📊 Case Técnico – Vaga Data Scientist

Este repositório contém a resolução do **case técnico** desenvolvido por **Bruno Gomes da Silva** como parte do processo seletivo para a posição de **Cientista de Dados**.

O estudo teve como objetivo analisar se a política interna de uma empresa farmacêutica, que busca **não discriminar salários por localização geográfica**, está sendo efetivamente cumprida.

---

## 🔍 Objetivo

Avaliar, por meio de análise de regressão, se existe diferença estatisticamente significativa nos salários dos colaboradores em função da variável **LOCATION** (capital vs. interior), controlando por outras variáveis como:

* Cargo
* Escolaridade
* Idade
* Experiência

---

## 🛠️ Metodologia

1. **Exploração dos dados** – tratamento de variáveis categóricas, verificação de valores ausentes e análise descritiva.
2. **Preparação dos dados** – encoding de variáveis, normalização quando necessário e seleção de features relevantes.
3. **Modelagem estatística** – aplicação de **Regressão Linear Múltipla** para medir a influência da localização nos salários.
4. **Validação** – verificação dos pressupostos do modelo e avaliação da significância estatística dos coeficientes.

---

## 📈 Principais Insights

* O fator **LOCATION** (capital vs. interior) **não apresentou efeito estatisticamente significativo** sobre os salários quando controladas variáveis como cargo e escolaridade.
* As variáveis que mais explicaram a variação salarial foram:

  * **Cargo** (posição na empresa);
  * **Nível de escolaridade**;
  * **Tempo de experiência**.
* Isso sugere que a política da empresa de **equidade salarial entre localidades** está sendo seguida.

---

## 🚀 Tecnologias Utilizadas

* Python (Pandas, NumPy, Statsmodels, Scikit-Learn, Matplotlib, Seaborn)
* Jupyter Notebook

---

## 📂 Estrutura do Repositório

* `Bruno_Gomes_da_Silva_Case_Técnico_Vaga_para_Data_Scientist.ipynb` → notebook principal com toda a análise.
* `data/` → base de dados utilizada no estudo.

---

## 📌 Conclusão

A análise mostrou que a **localização geográfica não impacta de forma significativa os salários**, validando a política da empresa de manter **equidade salarial independente da região**.

