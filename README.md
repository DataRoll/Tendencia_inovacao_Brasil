# Tendencia_inovacao_Brasil
Encontrar quais são são as próximas tendencias de inovação no Brasil?

1. Pergunta de Negócio
Quais são as próximas tendencias de inovação no Brasil?

2. Entendimento de Negócio
-Qual palavra dessa frase, ou combinações de palavras dessa frase, ou ainda sinônimos são mais cientificamente relevantes nessa pergunta?
- Buscar artigos em Pt e inglês escritos no Brasil
- Palavra chave → Inovação, tendências, predição, patentes, Innovation, forecast, prediction, trend, indicator, prognosis
- Coletar a quantidade de artigos/ano 

3. Coleta de dados

Publicações cientificas
Indicador de patentes, científicos e indicadores econômicos
pegar algumas palavras chave
Fazer buscas em periódicos científicos

Onde procurar? 
-Science direct (plataforma)
-Scopus
-Elsevier (editora)
-Scielo
-web oficescience
-dar uma diferenciada o que editora: scopus, scielo
-Existem 2 indicadores o INPI base abertos
Consegue ter acesso ao número de depósitos de patentes no Brasil
-WIPO análogo do INPI só que global


# Planejamento da solução

1. Saída: ( Produto final )
1.1  A resposta para a pergunta.
	- Indicar quais as próximas tendencias de inovação no Brasil
1.2 Formato da entrega
	- Clusterização com um conjunto de palavras para responder a pergunta
1.3 Local da entrega
	- Imagem PNG, App Streamlit,


2. Processo ( Passo a Passo)
1° Raspagem
- Fazer uma raspagem em revista cientificas com as palavras chaves
- Fazer um filtro com para apenas artigo, localização (Brazil)  e entre 2011 e 2020
- coletar a quantidade de publicações/ano
- salvar as duas colunas no formato .csv
- Fazer visualização utilizando o as bibliotecas Pyplot e Seabon para encontrar alguma tendencia visual
2° Raspagem
- Utilizar palavras chave utilizadas na 1° raspagem e fazer a pesquisa utilizando o filtro anteriormente.
Fazendo o download dos resumos na scopus
- clicar em “All” → “Export”
- Filtros: Abstract & Keywords + Year +Document title
- Fazer a clusterização no software VOSviewer


3. Entrada ( Fonte de dados )
3.1. Fonte de dados
-Science direct (plataforma)
-Scopus
-Elsevier (editora)
-Scielo
-web oficescience
-indicadores de patentes no Brasil WIPO análogo do INPI só que global

3.2. Ferramentas
- Python 3.8.0
- Jupyter Notebook
- Google Colab
- leitor txt
