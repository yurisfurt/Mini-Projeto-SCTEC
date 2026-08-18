Este projeto consistiu na análise exploratória de uma base de dados de varejo com mais de 700 mil registros. Abaixo, o resumo das etapas executadas:

Carga e Inspeção: Importação dos dados via Pandas e identificação da estrutura inicial (830.000 linhas e colunas residuais nulas).
Limpeza de Dados (Data Cleaning):

1. **Qualidade dos Dados**: Identificamos e removemos colunas irrelevantes (`Unnamed`) e aproximadamente 96 mil duplicatas, garantindo a integridade da análise.
Eliminação de 96.553 linhas duplicadas para garantir a unicidade das transações.
Ajuste do formato de data para padrão datetime brasileiro.
Análise Descritiva (Sprint 4):

2. **Perfil do Cliente**: A análise descritiva da coluna `CL_FHL` revelou um perfil de consumo majoritariamente composto por clientes sem filhos (mediana 0).
Identificação de que a maioria dos clientes (mediana 0) não possui filhos, com uma média de 1.15 por registro.

3. **Tratamento Temporal**: A conversão correta da coluna `DATA` permitiu a visualização precisa da amplitude do dataset (Fevereiro a Agosto de 2019).
Criação de gráfico de contagem (countplot) para entender a distribuição demográfica dos clientes.
Relatório Final (Sprint 5):
Geração de métricas consolidadas: 733.447 vendas processadas, 1.000 clientes únicos e 7 categorias de produtos analisadas.



