# Hackathon Ada Tech 2024

### Organiza��o do reposit�rio

1� Fa�am um clone do reposit�rio na sua m�quina local

2� Crie sua branch usando o comando:

      git checkout -b NomeDaSuaBranch

3� As contribui��es devem ser feitas pela branch criada  


# Explora��o do Conjunto de Dados dos Funcion�rios  

Este projeto tem como objetivo explorar e visualizar o conjunto de dados dos funcion�rios obtido de uma empresa. O conjunto de dados cont�m v�rias caracter�sticas dos funcion�rios, como g�nero, idade, ra�a, educa��o, endere�o, estado, tempo de casa, departamento e senioridade. A an�lise inclui limpeza de dados, visualiza��o de distribui��es e insights sobre as caracter�sticas da for�a de trabalho.

## Informa��es do Conjunto de Dados  

O conjunto de dados inclui as seguintes colunas:  

- `ID`: ID do funcion�rio
- `Nome`: Nome do funcion�rio
- `G�nero`: G�nero do funcion�rio
- `Idade`: Idade do funcion�rio
- `Ra�a`: Ra�a do funcion�rio
- `Forma��o`: N�vel de educa��o do funcion�rio
- `Endere�o`: Endere�o do funcion�rio
- `Estado`: Estado do funcion�rio
- `Tempo de Casa`: Tempo de perman�ncia do funcion�rio na empresa
- `Departamento`: Departamento onde o funcion�rio trabalha
- `Senioridade`: N�vel de senioridade do funcion�rio

## Limpeza e Prepara��o dos Dados  

- Removida a segunda coluna 'id'.
- Renomeadas as colunas para melhor legibilidade.
- Reordenadas as colunas.
- Padronizadas as categorias de g�nero.
- Capitalizadas as categorias de ra�a.
- Capitalizadas as categorias de educa��o.
- Padronizadas as categorias de senioridade.
- Substitu�do '\r\n' por ';' na coluna 'Endere�o'.
- Substitu�do ',' por ';' na coluna 'Endere�o'.
- Convertidas as colunas 'Idade' e 'Tempo de Casa' para o tipo inteiro.  

## Visualiza��o  

O projeto inclui visualiza��o de v�rias distribui��es no conjunto de dados:  

- Histograma da distribui��o de idade.
- Gr�fico de pizza mostrando a distribui��o de g�nero.
- Gr�fico de barras mostrando a distribui��o de ra�a.
- Gr�fico de barras mostrando a distribui��o de educa��o.
- Gr�fico de barras mostrando a distribui��o de estado.
- Gr�fico de barras mostrando a distribui��o de regi�o.
- Gr�fico de barras mostrando a distribui��o de departamento.
- Gr�fico de barras mostrando a distribui��o de senioridade.
- Histograma da distribui��o de tempo de casa.   

## Ferramentas e Bibliotecas  

O projeto foi implementado usando as seguintes ferramentas e bibliotecas:

- Python 3.11.7
- Pandas 2.1.4
- Matplotlib 3.8.0
- Seaborn 0.12.2
- Requests 2.31.0
- ftfy  6.2.0

## Como Usar  

- Clone este reposit�rio para sua m�quina local.
- Execute o arquivo Jupyter Notebook para explorar o conjunto de dados e as visualiza��es.
