# Avaliação de Métodos de Busca e Processamento de Dados

Este repositório contém a avaliação de diferentes métodos de busca e técnicas de pré-processamento de dados aplicados a um conjunto de consultas. Os resultados estão documentados em uma planilha, que consolida a performance de cada método para cada consulta.

## Estrutura do Repositório

```

LABELASTICSEARCH/

├── .venv/ # Ambiente virtual Python

├── data/ # Diretório contendo os conjuntos de dados

├── logs/ # Diretório para armazenamento de logs

├── .env # Arquivo de configurações e variáveis de ambiente

├── .gitignore # Arquivo de configuração do Git para ignorar arquivos

├── .tool-versions # Configuração de versões de ferramentas

├── docker-compose.yaml # Arquivo de configuração do Docker Compose

├── lab.ipynb # Notebook Jupyter com análises e execução de testes

├── README.md # Documentação principal do projeto

├── requirements.txt # Lista de dependências do Python

```

## Planilha de Avaliação

A planilha utilizada para avaliação está disponível no seguinte link:

[Planilha de Avaliação de Métodos](https://docs.google.com/spreadsheets/d/1gpo4oMvtHKggQOchTGzcUYLOct7ilU02vggO9y8bdgQ/edit?usp=sharing)

Cada aba da planilha representa um tipo de busca e pré-processamento diferente. Os resultados consolidados estão na aba "Gabaritos", que contém a performance de todas as buscas para cada consulta.

### Estrutura da Planilha

- **Gabaritos:** Resultados consolidados das buscas para cada query.

- **Diferentes Métodos de Busca:** Cada aba representa um método de busca e pré-processamento aplicado aos dados.

- **Métricas Avaliadas:** NDCG@K, DCG@K e outras métricas utilizadas para avaliar a relevância dos resultados retornados por cada método.

## Integrantes

- **Helena Sátyro** - [email](mailto:maria.helena.satyro.gomes.alves@ccc.ufcg.edu.br) - [GitHub](https://github.com/helenasatyro)

- **José Vitor Barbosa** - [email](mailto:jose.vitor.maciel@ccc.ufcg.edu.br) - [GitHub](https://github.com/vitorbarbosa123)

- **João Victor Lucena** - [email](mailto:joao.victor.lucena@ccc.ufcg.edu.br) - [GitHub](https://github.com/joaovictorsl)

- **Maya Brito** - [email](mailto:mayara.pinheiro@ccc.ufcg.edu.br) - [GitHub](https://github.com/MayaBrito)

- **Samuel Matos** - [email](mailto:samuel.lucas.vieira.matos@ccc.ufcg.edu.br) - [GitHub](https://github.com/SamuelLucasVM)

## Como Executar o Projeto

### Configuração do Ambiente

1. Clone este repositório:

```sh

git clone https://github.com/seu-repositorio.git

cd LABELASTICSEARCH

```

2. Crie um ambiente virtual e instale as dependências:

```sh

python3 -m venv .venv

source .venv/bin/activate # Linux/Mac

.venv\Scripts\activate # Windows

pip install -r requirements.txt

```

3. Configure o ambiente utilizando o arquivo `.env`.

4. Para executar as análises, utilize o notebook `lab.ipynb`.

### Utilização do Docker

Se preferir rodar o ambiente via Docker, utilize:

```sh

docker-compose up --build

```

## Contribuição

Se deseja contribuir, siga estas etapas:

1. Fork o repositório

2. Crie um branch (`git checkout -b feature/nova-feature`)

3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)

4. Envie para o branch principal (`git push origin feature/nova-feature`)

5. Abra um Pull Request

## Licença

Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo `LICENSE`.