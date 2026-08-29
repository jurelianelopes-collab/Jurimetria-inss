📊 Análise Jurimétrica de Benefícios Previdenciários do INSS
Este repositório contém o estudo de análise exploratória de dados (EDA) e jurimetria aplicada aos dados abertos de concessão de benefícios previdenciários do INSS.
📌 Visão Geral do Projeto
O objetivo desta análise é mapear o comportamento da concessão de benefícios previdenciários, identificando a taxa de judicialização, as principais matérias contestadas judicialmente, as patologias (CIDs) de maior litígio e o perfil demográfico dos beneficiários.
🛠️ Tecnologias e Ferramentas Utilizadas
Linguagem: Python 3
Ambiente de Desenvolvimento: Google Colab / Jupyter Notebook
Manipulação e Tratamento de Dados: Pandas
Visualização de Dados: Matplotlib, Seaborn
📊 Principais Insights Extraídos
Métrica / Indicador
Achado Principal
Impacto Jurimétrico
 
Taxa de Judicialização
~15,8% das concessões decorrem de Ação Judicial (80.698+ casos).
Indica alta taxa de divergência entre a perícia/análise administrativa do INSS e as decisões judiciais.
Espécies Mais Judicializadas
Aposentadoria por Idade e Auxílio-Doença Previdenciário.
Mostra concentração de litígios em comprovação de tempo/requisitos e incapacidade temporária.
Principais CIDs em Ações
M51.1 (Transtornos de discos intervertebrais) e M54.5 (Dor lombar baixa).
Patologias ortopédicas/coluna são o grande gargalo de indeferimento administrativo.
Perfil Etário
Concentração expressiva entre 40 e 60 anos na via judicial.
Faixa etária de transição de carreira e maior incidência de incapacidades laborais.

📁 Estrutura do Repositório
├── README.md                              # Apresentação do projeto
├── notebooks/
│   └── analise_jurimetrica_inss.ipynb    # Código completo no Google Colab
└── data/
    └── D.SDA.PDA.001.CON.202305.json     # Base de dados (formato JSON)


🚀 Como Executar o Projeto
Clone este repositório para o seu ambiente local:
git clone https://github.com/seu-usuario/jurimetria-inss.git
Faça upload do arquivo .ipynb no Google Colab ou abra em um ambiente Jupyter.
Certifique-se de carregar a base de dados JSON (utilizando o encoding latin1 e normalizando a coluna nodes via pd.json_normalize).
Execute as células em sequência para gerar os relatórios e visualizações.
