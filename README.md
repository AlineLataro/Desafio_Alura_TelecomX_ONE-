## 💡 Escopo do Projeto

Este projeto tem como objetivo analisar a evasão de clientes (churn) na empresa fictícia **Telecom X**, identificando os principais fatores que levam ao cancelamento de contratos. A análise foi conduzida com foco em:

- Limpeza e tratamento de dados.
- Exploração estatística e visual das variáveis.
- Identificação de padrões de comportamento entre clientes que cancelaram e os que permaneceram.
- Geração de insights que possam embasar **estratégias de retenção** de clientes.

---

## 🛠 Tecnologias e Ferramentas Utilizadas

- **Linguagem:** Python 3
- **Bibliotecas de análise de dados:**
  - `pandas`
  - `numpy`
- **Bibliotecas de visualização:**
  - `matplotlib`
  - `seaborn`
- **Ambiente de desenvolvimento:** Google Colab
- **Armazenamento de gráficos:** Google Drive
- **Documentação e Apresentação:** Markdown (`README.md`)

---

## 🚧 Desafios Enfrentados

Durante o desenvolvimento do projeto, enfrentamos e superamos os seguintes desafios:

- **Padronização dos dados**: várias colunas estavam com valores inconsistentes, como campos `Yes/No` que precisaram ser convertidos em valores binários para facilitar análises estatísticas.
- **Colunas mal formatadas**: como a coluna de total gasto (`Charges.Total`) contendo dados numéricos em formato de texto, exigindo conversão e tratamento de valores ausentes.
- **Visualizações com muitas categorias**: ajustar cores, legendas e categorias em gráficos com múltiplas variáveis foi um ponto importante para garantir clareza.
- **Integração com Google Drive**: garantir que os gráficos salvos fossem corretamente exibidos no Google Collab utilizando links públicos e adaptando o tamanho via HTML.

---
