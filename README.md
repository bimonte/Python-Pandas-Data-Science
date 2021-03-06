# Python-Pandas-Data-Science
Usando o pacote Pandas em problemas reais de Data Science.

## Motivação
A internet é nossa maior aliada no processo de aprendizado. Existem infinitas fontes de informação que nos ajudam a aprender de uma forma bem rápida sobre qualquer assunto, desde que estejamos realmente dispostos e motivados.

Entretanto, isso também é uma dificuldade, uma vez que as informações estão espalhadas e muitas vezes precisamos consultar diversas fontes para resolver uma questão.

Por isso, fiz um resumo nesse repositório de algumas atividades reais do dia-a-dia típico de um trabalho de análise de dados que fazem uso de diversos métodos e propriedades do pacote Pandas do Python, desde o mais básico até o avançado.

Claro que eu não pretendo esgotar o assunto aqui, mas de qualquer modo um grande escopo de informações sobre o Pandas será abordado.

Eu acredito que o exemplo ensina muito mais do que a teoria. Então vamos direto para a prática!

## Início
Para ficar bem à vontade e explorar esse repositório, você tem duas opções:

* Fazer um fork dele (cópia) para o seu usuário. Confira como fazer isso aqui: https://help.github.com/en/github/getting-started-with-github/fork-a-repo .
* Fazer o download clicando no botão verde "Code" e depois em "Download ZIP". Dessa forma, você terá todos os arquivos na sua máquina diretamente para edição e testes.

Para instalar o Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html<br />
Para instalar o pacote Pandas: https://pandas.pydata.org/pandas-docs/stable/install.html

## Contextualização
Esse repositório acompanha meu vídeo "Usando o Pandas em problemas reais de Data Science" ([Parte 1](https://youtu.be/6vUqhrnNyF0)) e ([Parte 2](https://youtu.be/DFrNTmA0ugU)). 

No vídeo, eu uso o Pandas e o Matplotlib para analisar dados de vendas e solucionar problemas que encontramos no trabalho diariamente.

A base de dados representam 12 meses de vendas de milhares de produtos eletrônicos, abertos por mês, tipo de produto, custo, endereço etc.

O primeiro passo do nosso trabalho é a limpeza dos dados, que inclui:
* Eliminar valores nulos e NaN (not a number).
* Remover linhas aplicando filtros.
* Alterar tipos de coluna (número, texto, data etc.).

Uma vez deixada a base bem limpa, com informações consistentes, seguimos para a parte de exploração. Aqui vamos focar em questões mais contundentes no que diz respeito aos nossos dados:
* Qual foi o melhor mês de vendas? Quanto foi vendido neste mês?
* Que cidade teve a maior quantidade de vendas?
* Em quais horários é maior a probabilidade de receber pedidos de clientes pelos canais de venda?
* Quantos produtos são vendidos em cada OV? Qual a dispersão dessa taxa ao longo do dia?
* Qual o produto mais vendido? Avalie o motivo de esse produto ser o mais vendido.
* Quais produtos são mais vendidos em conjunto (bundle), considerando pelo menos 2 produtos?

Para isso, vamos usar uma série de métodos e propriedades do Pandas e do Matplotlib:
* Concatenar múltiplos arquivos para criar um único DataFrame.
* Criar colunas com base em outras.
* Dividir o conteúdo de colunas em múltiplas novas colunas.
* Aplicar uma função ao longo de uma ou mais colunas.
* Agrupar linhas e sumarizar informações.
* Aplicar transformações em agrupamentos de colunas.
* Gerar gráficos customizados de fácil visualização.
