Projeto Imobiliária – Análise com Pandas e Python

Este projeto consiste em uma análise exploratória de dados do mercado imobiliário, utilizando a biblioteca Pandas do Python.
O dataset contém informações sobre imóveis para aluguel, permitindo explorar características, filtrar informações relevantes e gerar insights.

Objetivos do Projeto:

* Explorar dados iniciais da base imobiliária.
* Calcular estatísticas descritivas (média, valores por tipo de imóvel, etc.).
* Identificar a média de aluguel por tipo de imóvel.
* Excluir imóveis comerciais para análise mais focada.
* Calcular percentual de cada tipo de imóvel na base.
* Explorar características de apartamentos (quartos, bairros, média de valores).
* Tratar valores nulos e registros inconsistentes.
* Criar filtros personalizados para imóveis de acordo com critérios (nº de quartos, valor do aluguel, área, etc.).
* Salvar resultados filtrados em arquivos CSV.

Estrutura do Projeto:

1. **Importação da Base de Dados**

   * Leitura de arquivo CSV hospedado no GitHub da Alura.

2. **Análise Exploratória de Dados (EDA)**

   * Visualização de registros iniciais e finais.
   * Informações gerais sobre colunas e tipos de dados.
   * Agrupamento por tipo de imóvel e cálculo de médias.

3. **Tratamento dos Dados**

   * Remoção de imóveis comerciais.
   * Preenchimento e exclusão de valores nulos.
   * Eliminação de registros inválidos (aluguel/condomínio = 0).

4. **Filtros e Consultas**

   * Apartamentos de 1 quarto com aluguel menor que R$ 1200.
   * Apartamentos com 2 ou mais quartos, aluguel < R$ 3000 e área > 70m².
   * Imóveis com área > 80m² ou aluguel < R$ 4000.

5. **Exportação de Resultados**

   * Criação de arquivos CSV com os datasets tratados e filtrados.

Tecnologias Utilizadas:

* **Python 3**
* **Pandas**
* **Matplotlib** (para gráficos simples)
* Google Colab

Exemplos de Análises:

* **Média de aluguel por tipo de imóvel (sem imóveis comerciais):**
  Gráfico Média de Aluguel.

* **Percentual de cada tipo de imóvel:**
  Representado em gráfico de barras.

* **Bairros com aluguel médio mais elevado:**
  Filtro aplicado para identificar regiões com maior preço de aluguel.

Resultados Gerados:

* `dados_apartamentos.csv` → Base final limpa com apartamentos.
* `dados_1.csv` → Apartamentos de 1 quarto e aluguel < R$ 1200.
* `dados_2.csv` → Apartamentos com 2+ quartos, aluguel < R$ 3000 e área > 70m².
* `dados_3.csv` → Apartamentos com área > 80m² ou aluguel < R$ 4000.

Fonte dos Dados:

Os dados utilizados foram disponibilizados pela [Alura Cursos](https://github.com/alura-cursos/pandas-conhecendo-a-biblioteca).

Autor

Desenvolvido por **Igor Gomes Leopoldino**
Contato: igorleopoldino18@gmail.com
[LinkedIn](https://linkedin.com/in/igor-leopoldino/)
