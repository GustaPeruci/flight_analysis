# Análise de Atrasos em Voos no Brasil (2022-2024)

## Sobre o Projeto

Quem nunca ficou esperando no aeroporto por causa de um voo atrasado? Este trabalho mergulha nos dados oficiais de **mais de 2,8 milhões de voos** domésticos no Brasil para descobrir onde e quando os atrasos mais acontecem.

### Principais Descobertas

- **Aeroportos "campeões" dos atrasos** identificados
- **Evolução temporal**: como a situação mudou entre 2022-2024  
- **Dias e horários críticos** para evitar em viagens
- **Ranking de pontualidade** das companhias aéreas brasileiras

## Metodologia

### Fontes de Dados
- **ANAC**: Dados oficiais de voos (2022-2024)
- **OpenFlights**: Base de aeroportos e companhias aéreas
- **Escopo**: Apenas voos com origem em território brasileiro

### Tecnologias Utilizadas
- **Python**: Processamento e análise
- **Pandas**: Manipulação de dados
- **Matplotlib/Seaborn**: Visualizações
- **Jupyter**: Ambiente de desenvolvimento

## Como Visualizar

**[Ver Análise Completa](./analise_atrasos_voos.ipynb)** - Clique para abrir o notebook com toda a investigação

## Estrutura do Projeto

```
flight_analysis/
│
├── analise_atrasos_voos.ipynb    # Notebook principal com toda a análise
├── airport-codes.csv             # Base de dados de aeroportos
├── airlines-codes.csv            # Base de dados de companhias aéreas  
├── historico_voos/              # Dados históricos por ano/mês
│   ├── 2022/                    # Dados de 2022
│   ├── 2023/                    # Dados de 2023
│   └── 2024/                    # Dados de 2024
├── requirements.txt             # Dependências Python
└── README.md                    # Este arquivo

```

## Executar Localmente

### Pré-requisitos
- Python 3.8+
- Jupyter Notebook

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GustaPeruci/flight_analysis.git
cd flight_analysis

# Instale as dependências
pip install -r requirements.txt

# Execute o Jupyter
jupyter notebook analise_atrasos_voos.ipynb
```

## Principais Insights

### Aeroportos
- **Identificação** dos aeroportos com maior volume de atrasos
- **Tendências** de melhoria e piora entre 2022-2024
- **Análise normalizada** por volume de operações

### Padrões Temporais
- **Dias da semana** mais problemáticos para viajar
- **Horários críticos** com maior probabilidade de atraso
- **Evolução mensal** da pontualidade ao longo dos anos

### Companhias Aéreas
- **Ranking de pontualidade** das principais companhias
- **Evolução do desempenho** ao longo do tempo
- **Análise comparativa** com volume significativo de voos

## Contexto Acadêmico

Este projeto foi desenvolvido como parte do curso de **Engenharia de software** para a aula de **Ciência de dados** e demonstra:

- **Tratamento de dados reais** com problemas típicos (encoding, dados inconsistentes)
- **Engenharia de features** para análise temporal
- **Visualizações informativas** e profissionais
- **Insights práticos** baseados em evidências

## Contato

**Gustavo Peruci**
- Email: [seu-email]
- LinkedIn: [seu-linkedin]  
- GitHub: [@GustaPeruci](https://github.com/GustaPeruci)

## Licença

Este projeto está sob a licença MIT. Dados utilizados são de fontes públicas (ANAC).
