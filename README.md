# Análise Exploratória dos Microdados ENEM 2023

Este projeto realiza uma análise exploratória dos microdados do ENEM 2023, com o objetivo de identificar padrões e relações entre características socioeconômicas e o desempenho dos participantes.

## 🎯 Objetivos

- Qual a relação entre renda familiar e desempenho no ENEM?
- Há diferença de desempenho entre estudantes de escolas públicas e privadas?
- Qual o desempenho médio por estado (UF)?
- A cor/raça do estudante influencia o desempenho médio?
- Quais variáveis socioeconômicas mais impactam a nota da redação ou média geral?

## 📁 Estrutura

- `data/`: contém os dados utilizados (baixado automaticamente do Google Drive)
- `notebooks/`: notebooks com análises e visualizações
- `scripts/`: scripts auxiliares para transformação e limpeza
- `outputs/`: gráficos e tabelas geradas
- `requirements.txt`: lista de bibliotecas necessárias

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/analise-microdados-enem-2023.git
   cd analise-microdados-enem-2023
   ```

2. Instale os pacotes necessários:
   ```bash
   pip install -r requirements.txt
   ```

3. Baixe os dados automaticamente (recomendado)

   Por conta do tamanho do arquivo, o dataset `MICRODADOS_ENEM_2023.csv` **não está presente neste repositório**.

   No entanto, o notebook está preparado para **baixá-lo automaticamente do Google Drive** na primeira execução.  
   O arquivo será salvo na pasta `data/`, como esperado pelo código.

   > ⚠️ Certifique-se de rodar todas as células do notebook sem modificações.

   📎 Caso deseje baixar manualmente:  
   [Clique aqui para acessar o arquivo no Google Drive](https://drive.google.com/file/d/1ofVd75SS5366pp8vDH20YDy-3cNP502b/view?usp=sharing)

4. Execute os notebooks localizados na pasta `notebooks/`

## 🧰 Requisitos

- Python 3.8+
- Pandas, Matplotlib, Seaborn, gdown (veja `requirements.txt`)

## 📄 Licença

MIT License
