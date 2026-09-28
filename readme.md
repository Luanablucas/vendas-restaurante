# Análise de vendas de um restaurante

Projeto iniciante de análise de dados com Python, utilizando vendas
fictícias de um restaurante entre janeiro e junho de 2026.

## Objetivo

Investigar o faturamento, os produtos mais vendidos e as diferenças
de vendas entre meses e dias da semana.

## Ferramentas utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Tratamento dos dados

- Preenchimento de categorias e preços ausentes com base nos registros
  dos mesmos produtos.
- Identificação de pagamentos ausentes como "Não informado".
- Padronização da escrita de Pix e remoção de espaços extras nos produtos.
- Correção de dois preços discrepantes para este exercício, usando
  os preços habituais dos produtos.
- Separação de três registros com quantidade zero para revisão.
- Conversão da coluna de datas e criação do valor total de cada linha.

A base original contém 4.312 registros. A análise utiliza 4.309 registros.

## Principais resultados

- Faturamento total: R$ 126.343,00.
- Prato feito liderou em faturamento e quantidade vendida.
- Maio apresentou o maior faturamento mensal.
- Sábado e domingo tiveram as maiores médias de faturamento diário.

## Limitações

Os dados são fictícios e foram criados para estudo.
O faturamento não representa lucro, pois não há informações sobre custos.


## Como executar

1. Instale o Python e baixe este projeto.
2. Abra um terminal na pasta principal do projeto.
3. Crie um ambiente virtual:

   ```powershell
   python -m venv .venv
   ```

4. Ative o ambiente no Windows PowerShell:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

5. Instale as bibliotecas necessárias:

   ```powershell
   python -m pip install pandas matplotlib ipykernel
   ```

6. Abra `notebooks/analise_vendas.ipynb` no VS Code, com as extensões
   Python e Jupyter instaladas.
7. Selecione o ambiente `.venv` como kernel do notebook.
8. Execute as células de cima para baixo.

O notebook utiliza o arquivo original `data/vendas_restaurante.csv`.