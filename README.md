# Case Técnico — Análise de Oportunidades de Negócio INSS

Este repositório apresenta a resolução de um **case técnico** voltado à **análise de dados de benefícios concedidos pelo INSS**, com foco na **identificação de oportunidades de negócio** e **viabilidade financeira** para expansão de uma rede de agências e lançamento de produtos de crédito.

---

## 🎯 Objetivo

A análise busca responder às seguintes perguntas de negócio:

1. **Identificação das Cidades Mais Atrativas:**  
   Quais são as 30 cidades mais promissoras para a expansão de uma rede de agências?

2. **Análise de Viabilidade Financeira:**  
   Qual a viabilidade do projeto, considerando o ponto de equilíbrio e o tempo de retorno do investimento?

3. **Impacto da Duração dos Benefícios:**  
   Como a rotatividade de beneficiários (temporários vs. permanentes) afeta o breakeven?

4. **Potencial de Novo Produto:**  
   Qual o potencial de receita e lucro de um novo produto de crédito consignado voltado a beneficiários permanentes?

---

## 📁 Estrutura do Repositório

- **`Case Dados.pdf`** — Documento original com a descrição do case técnico, perguntas de negócio e premissas.  
- **`analise_case_inss.ipynb`** — Jupyter Notebook contendo o código Python completo da análise (carregamento, limpeza, cálculos, visualizações e respostas).  
- **`Apresentacao.pdf`** — Apresentação dos resultados e principais insights de negócio obtidos.  
- **`README.md`** — Este arquivo, com a descrição do projeto e instruções de reprodução.

---

## ⚙️ Como Reproduzir a Análise

### 1. Pré-requisitos

- Python 3.x  
- Jupyter Notebook ou JupyterLab  
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `pathlib`

### 2. Dados

- Os dados em formato `.xlsx` não estão incluídos no repositório devido ao tamanho.  
  O link para download encontra-se no arquivo **Case Dados.pdf**.  
- Após o download, crie uma pasta chamada `dados` na raiz do projeto e coloque os arquivos `.xlsx` dentro dela.

### 3. Execução

1. Abra o arquivo `analise_case_inss.ipynb` em seu ambiente Jupyter.  
2. Execute as células em ordem para reproduzir a análise completa.

---

## 📈 Resumo dos Resultados

A análise indica **alta viabilidade do projeto de expansão**, com os seguintes destaques:

- **Breakeven rápido:** o ponto de equilíbrio para 30 agências é alcançado em menos de um mês, mesmo com alta rotatividade.  
- **Concentração geográfica:** apenas 30 cidades concentram **22,7% dos novos benefícios**, permitindo uma estratégia de expansão focada.  
- **Potencial de lucro adicional:** o produto de crédito consignado para beneficiários permanentes pode gerar **lucro líquido estimado em R$ 75 milhões em 30 meses**.

---

## 💡 Principais Insights de Negócio

1. **Oportunidade massiva:** o mercado de beneficiários do INSS apresenta volume expressivo e constante de novos clientes.  
2. **Concentração geográfica:** o foco nas 30 principais cidades otimiza a estratégia de expansão.  
3. **Viabilidade excepcional:** o breakeven é atingido em menos de 1 mês, mesmo com alta rotatividade.  
4. **Modelo resiliente:** o alto volume de novos clientes compensa amplamente o churn.  
5. **Cross-sell:** o crédito consignado oferece forte potencial adicional de receita e lucro.

---

## 🚀 Recomendações Estratégicas

- **Fase 1:** Implementar agências nas Top 10 cidades (≈49% do volume das 30 principais).  
- **Fase 2:** Expandir para as demais cidades após validação do modelo inicial.  
- **Foco no cliente:** Priorizar beneficiários permanentes (maior lifetime value).  
- **Cross-sell:** Introduzir o produto de crédito consignado após 3–6 meses de operação.
