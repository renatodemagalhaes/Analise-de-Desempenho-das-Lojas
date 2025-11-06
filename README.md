
# 🏬 Projeto: Análise de Desempenho das Lojas — Alura Store

## 📘 Descrição

Este projeto tem como objetivo **analisar dados de vendas, desempenho e avaliações de quatro lojas fictícias da Alura Store**, identificando qual delas apresenta **menor eficiência operacional** e fornecendo **uma recomendação estratégica final** baseada nos dados coletados.

A análise foi desenvolvida em **Python**, utilizando **Google Colab** e bibliotecas como `pandas`, `matplotlib` e `numpy` para manipulação, visualização e interpretação dos dados.

---

## 🎯 Objetivos da Análise

1. Calcular o **faturamento total** de cada loja.  
2. Avaliar a **média das avaliações dos clientes**.  
3. Calcular o **custo médio de frete** por loja.  
4. Identificar as **categorias e produtos mais e menos vendidos**.  
5. Determinar um **índice geral de eficiência** combinando métricas financeiras e de satisfação.  
6. **Recomendar a loja que deve ser vendida** com base nos resultados consolidados.

---

## 🧠 Metodologia

A análise foi conduzida em etapas:

- **Carregamento dos dados** de 4 arquivos CSV (`loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv`);
- **Limpeza e normalização** das colunas numéricas (`Preço`, `Frete`, `Avaliação`);
- **Cálculo de indicadores**: faturamento, média de avaliações, custo médio de frete;
- **Criação de um índice de eficiência ponderado**, com pesos ajustados para cada critério:
  - Faturamento → 50%
  - Avaliação dos clientes → 30%
  - Custo médio de frete → 20%
- **Visualizações gráficas** para apoio à decisão:
  - Gráfico de barras (faturamento total);
  - Gráfico de eficiência (índice geral);
  - Gráfico de radar (comparativo multidimensional entre as lojas).

---

## 📊 Resultados

Os gráficos e relatórios gerados demonstraram o desempenho geral de cada loja.  
A **loja com menor eficiência** apresentou:
- Faturamento mais baixo,  
- Maior custo médio de frete, e  
- Avaliações médias inferiores.  

Com base nessas evidências, foi feita uma **recomendação final ao Sr. João** para vender a loja menos eficiente e concentrar investimentos nas lojas mais rentáveis e bem avaliadas.

---

## 🧩 Tecnologias Utilizadas

- Python 3.x  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  
- IPython Markdown (para relatório formatado)

---

## 🏁 Conclusão

Este projeto demonstra como a análise de dados pode **embasar decisões de negócio de forma quantitativa e visual**, integrando diferentes dimensões — financeira, logística e de satisfação do cliente — em um diagnóstico claro e acionável.

---

## 📂 Estrutura do Projeto

```
📦 alura-store-analysis
├── loja_1.csv
├── loja_2.csv
├── loja_3.csv
├── loja_4.csv
├── analise_lojas.ipynb
└── README.md
```

---

## ✨ Autor

**Desenvolvido por:** [Seu Nome Aqui]  
📧 Contato: seu.email@exemplo.com  
💼 GitHub: [https://github.com/seuusuario](https://github.com/seuusuario)
