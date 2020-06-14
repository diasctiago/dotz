# Hackathon Dotz 2020

## Aqui você encontra!

A solução apresentada para o Hackathon Dotz 2020

### Dotz

Dotz é um programa de benefícios que agrega empresas, como bancos, supermercados, livrarias, cinemas, postos de gasolinas drogarias, etc. Consiste basicamente no acúmulo de pontos através de compras nestes estabelecimentos, para serem trocados por prêmios e serviços oferecidos.

### Hackathon Dotz

O desafio é desenvolver um código para cadastro e categorização automáticas de novos produtos da estrutura mercadológica da Dotz.

### Arquivos

* model.ipynb - Notebook com a solução apresentada
* train.csv - Arquivo com os dados (DESCRIÇÃO PARCEIRO,SUB-CATEGORIA,CATEGORIA,DEPARTAMENTO), utilizado para treinamento do modelo
* test.csv - Arquivo com os dados (DESCRIÇÃO PARCEIRO), utilizado para teste do modelo
* result.csv - Arquivo com os dados (DESCRIÇÃO PARCEIRO,SUB-CATEGORIA,CATEGORIA), utilizado para validação do modelo e submissão do hackathon

### Executando o Notebbok

Para executar o notebook **model.ipynb** precisam estar no mesmo diretório do notebook um arquivo de treinamento (Nome: **train.csv**, Colunas: DESCRIÇÃO PARCEIRO,SUB-CATEGORIA,CATEGORIA,DEPARTAMENTO) e o arquivo que deseja fazer a classificação (Nome: **test.csv**, Coluna: DESCRIÇÃO PARCEIRO), após a execução vai ser gerado no mesmo diretório um arquivo com a classificação (Nome: **result.csv**, Colunas: DESCRIÇÃO PARCEIRO,SUB-CATEGORIA,CATEGORIA).

### Contatos

Email: diasctiago@gmail.com

GitHub: https://github.com/diasctiago

LinkedIn: https://www.linkedin.com/in/diasctiago/
