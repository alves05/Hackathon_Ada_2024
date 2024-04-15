# Hackathon Ada Tech 2024

### Organização do repositório

1° Façam um clone do repositório na sua máquina local

2° Crie sua branch usando o comando:

      git checkout -b NomeDaSuaBranch

3° As contribuições devem ser feitas pela branch criada  


# Exploração do Conjunto de Dados dos Funcionários  

Este projeto tem como objetivo explorar e visualizar o conjunto de dados dos funcionários obtido de uma empresa. O conjunto de dados contém várias características dos funcionários, como gênero, idade, raça, educação, endereço, estado, tempo de casa, departamento e senioridade. A análise inclui limpeza de dados, visualização de distribuições e insights sobre as características da força de trabalho.

## Informações do Conjunto de Dados  

O conjunto de dados inclui as seguintes colunas:  

- `ID`: ID do funcionário
- `Nome`: Nome do funcionário
- `Gênero`: Gênero do funcionário
- `Idade`: Idade do funcionário
- `Raça`: Raça do funcionário
- `Formação`: Nível de educação do funcionário
- `Endereço`: Endereço do funcionário
- `Estado`: Estado do funcionário
- `Tempo de Casa`: Tempo de permanência do funcionário na empresa
- `Departamento`: Departamento onde o funcionário trabalha
- `Senioridade`: Nível de senioridade do funcionário

## Limpeza e Preparação dos Dados  

- Removida a segunda coluna 'id'.
- Renomeadas as colunas para melhor legibilidade.
- Reordenadas as colunas.
- Padronizadas as categorias de gênero.
- Capitalizadas as categorias de raça.
- Capitalizadas as categorias de educação.
- Padronizadas as categorias de senioridade.
- Substituído '\r\n' por ';' na coluna 'Endereço'.
- Substituído ',' por ';' na coluna 'Endereço'.
- Convertidas as colunas 'Idade' e 'Tempo de Casa' para o tipo inteiro.  

## Visualização  

O projeto inclui visualização de várias distribuições no conjunto de dados:  

- Histograma da distribuição de idade.
- Gráfico de pizza mostrando a distribuição de gênero.
- Gráfico de barras mostrando a distribuição de raça.
- Gráfico de barras mostrando a distribuição de educação.
- Gráfico de barras mostrando a distribuição de estado.
- Gráfico de barras mostrando a distribuição de região.
- Gráfico de barras mostrando a distribuição de departamento.
- Gráfico de barras mostrando a distribuição de senioridade.
- Histograma da distribuição de tempo de casa.   

## Ferramentas e Bibliotecas  

O projeto foi implementado usando as seguintes ferramentas e bibliotecas:

- Python
- Pandas
- Matplotlib
- Seaborn
- Requests
- ftfy  

## Como Usar  

- Clone este repositório para sua máquina local.
- Execute o arquivo Jupyter Notebook para explorar o conjunto de dados e as visualizações.
