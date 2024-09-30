# Analise-de-Fatores-de-Saude-Relacionados-ao-Diabetes

## 1. Resumo do Projeto
Este projeto realiza uma análise exploratória dos dados de saúde relacionados ao diabetes, visando entender como diferentes fatores, como **Índice de Massa Corporal (IMC)**, **atividade física**, e **hábitos alimentares** (como o consumo de frutas) influenciam a prevalência do diabetes. A análise é baseada em um conjunto de dados de saúde que contém variáveis demográficas, comportamentais e clínicas.

## 2. Objetivo
O objetivo principal deste projeto é identificar fatores significativos que contribuem para o desenvolvimento de diabetes e entender suas relações por meio de visualizações e testes estatísticos. Com isso, pretendemos oferecer insights que possam ser utilizados na prevenção e no gerenciamento do diabetes.

## 3. Conjunto de Dados
- **Fonte**: O conjunto de dados contém informações demográficas, clínicas e comportamentais dos indivíduos.
- **Principais Variáveis**:
  - `Diabetes_012`: Status de diabetes (0 = sem diabetes, 1 = pré-diabetes, 2 = diabetes).
  - `BMI`: Índice de Massa Corporal.
  - `HighBP`: Pressão alta (0 = não, 1 = sim).
  - `PhysActivity`: Prática de atividade física (0 = não, 1 = sim).
  - `Fruits`: Consumo de frutas (0 = não, 1 = sim).
  - `Veggies`: Consumo de vegetais (0 = não, 1 = sim).
  - `Income`: Faixa de renda.

## 4. Análises Realizadas
### 4.1 Limpeza e Preparação dos Dados
- **Remoção de duplicatas** e **tratamento de valores nulos** foram realizados para garantir a integridade dos dados.
- **Tratamento de outliers**: Identificação e análise dos valores extremos nas variáveis contínuas, como IMC.

### 4.2 Estatísticas Descritivas
- **Análise de distribuição** das principais variáveis, como IMC, consumo de frutas e atividade física.
- **Média**, **mediana**, **desvio padrão** e **frequência** foram calculados para entender as características dos dados.

### 4.3 Visualizações
- **Gráfico de Violino**: Mostra a distribuição do IMC nos diferentes grupos de diabetes, destacando diferenças entre os grupos.
- **Gráfico de Dispersão**: Relaciona o IMC com a idade e o status de diabetes, evidenciando possíveis tendências.
- **Gráfico de Barras**: Mostra a relação entre o consumo de frutas e o status de diabetes.

### 4.4 Testes Estatísticos
- **Matriz de Correlação**: Calculada para identificar variáveis com fortes relações entre si e com o status de diabetes.
- **Teste ANOVA**: Avalia a diferença no IMC entre grupos de diabetes (sem diabetes, pré-diabetes, diabetes).
- **Teste Qui-Quadrado**: Verifica a associação entre a prática de atividade física e o status de diabetes.

## 5. Principais Conclusões
- **IMC Elevado** está significativamente associado a um maior risco de diabetes. A mediana do IMC é mais alta nos indivíduos com diabetes.
- **Atividade Física**: O teste de hipótese mostrou que a prática de atividade física tem um impacto significativo na prevalência de diabetes.
- **Consumo de Frutas**: Indivíduos que consomem frutas regularmente tendem a ter uma menor prevalência de diabetes.

## 6. Organização dos Arquivos
- **Código e Análises**: O código Python e as análises foram realizados em um Jupyter Notebook, facilitando a reprodutibilidade.
- **Gráficos e Visualizações**: Foram criados gráficos de dispersão, gráficos de violino, e gráficos de barras para ilustrar os insights.
- **Apresentação**: Foi gerada uma apresentação executiva (em PDF) contendo os principais resultados e conclusões para fácil visualização.

## 7. Como Executar o Projeto
1. **Requisitos**: Python 3.x, Jupyter Notebook, bibliotecas (`pandas`, `seaborn`, `matplotlib`, `scipy`).
2. **Passos**:
   - Abra o arquivo Jupyter Notebook (`.ipynb`) no Jupyter.
   - Execute as células sequencialmente para carregar, limpar e analisar os dados.
   - Os gráficos e as análises serão gerados automaticamente durante a execução.
