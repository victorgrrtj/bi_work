<!-- antes de enviar a versão final, solicitamos que todos os comentários, colocados para orientação ao aluno, sejam removidos do arquivo -->
# Trabalho Final de BI

#### Aluno: [Victor Ribeiro](https://github.com/victorgrrtj)
#### Aluna: [Thaís Guarize](https://github.com/victorgrrtj)
#### Orientador: [Leonardo Mendonza](https://github.com/link_do_github)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "BI - Business Intelligence".

[Trabalho_BI.ipynb](https://github.com/victorgrrtj/bi_work/blob/main/Trabalho_BI.ipynb)

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

O objetivo deste trabalho é realizar uma WordCloud a partir de uma base de dados lida de um arquivo json.

### Abstract <!-- Opcional! Caso não aplicável, remover esta seção -->

<!-- trocar o texto abaixo pelo resumo do trabalho, em inglês -->

The work's purpose is to build a wordcloud based on a json file.

### 1. Introdução

- Base de Dados: [LINK](https://github.com/victorgrrtj/bi_work/blob/main/data_2021-11-21%2023_36_01.258822.json)

A base é um arquivo json que contém dados sobre aluguel e venda de imóveis. O objetivo é criar wordclouds com base nas colunas de títulos, descrição e tipo de imóvel.

### 2. Modelagem

A Wordcloud foi elaborada com a biblioteca Worcloud e Matpotlib. Para tal, realizamos a junção de todas as linhas para criação de um vetor de tokens. Após a tokenização, utilizamos o pacote Stopword para limpar os tokens sem significado relevante. Então, geramos a wordcloud para cada coluna (titulo, descrição e tipo).

### 3. Resultados

Os resultados foram satisfatórios visto que as wordclouds impressas informaram os dados relevantes mais frequentes.

### 4. Conclusões

Concluímos que a elaboração das Wordclouds permitiram visualizar as maiores ofertas de localização, tipos de imóveis e informações mais frequentes na descrição dos anúncios. Somos gratos ao professor Leonardo Mendonza que demonstrou muito bem como elaborar modelos de Wordcloud. Conforme relatado em aula, não existe um modelo perfeito pois há diversas formas de chegar ao mesmo resultado.

---

Matrícula Victor: 211.100.047

Matrícula Thaís: 211.100.376

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
