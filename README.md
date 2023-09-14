## Teste técnico
O arquivo *teste.ipynb* contém o código do teste. De acordo com as células, o código realiza: 
1. Importação das bibliotecas necessárias.
2. Cria lista das colunas necessárias.
3. Importa os arquivos da URL e salva em variáveis.
4. Seleciona apenas a palavra necessária da coluna "DS_ITEM".
5. Remove caracteres especiais e coloca as palavras em caixa baixa.
6. Seleciona valores com contagem acima de 2.500.
7. Cria tabela com estatísticas descritivas.
8. Remove variáveis desnecessárias.

A fim de se reduzir a quantidade de arquivos que seriam enviados para o GitHub, o código baixa os arquivos a partir de uma URL.
**Os caminhos em que os arquivos são salvos devem ser modificados de acordo com o caminho utilizado**


### Resultados e Discussão
Os cinco principais itens de compra de orgãos públicos do Rio Grande do Sul e suas respectivas estatísticas descritivas (média, mediana, desvio padrão, valor máximo e mínimo) do valor de compra de cada item, nos anos de 2016 a 2019, estão apresentadas nas Figuras de 1 a 4.

![image](https://user-images.githubusercontent.com/96580515/175964578-c7c2bab8-1fe0-49e8-a78d-d7a00098248d.png)
|:--:| 
| *Figura 1. Estatística descritiva dos cinco itens mais frequentes de compra do ano de 2016.* |


![image](https://user-images.githubusercontent.com/96580515/175963184-9a12a2dc-4d64-4ec7-9ed0-3605f46759e7.png)
|:--:| 
| *Figura 2. Estatística descritiva dos cinco itens mais frequentes de compra do ano de 2017.* |


![image](https://user-images.githubusercontent.com/96580515/175962498-b84d6b28-44f5-4766-9dc3-489a3fe0aabb.png)
|:--:| 
| *Figura 3. Estatística descritiva dos cinco itens mais frequentes de compra do ano de 2018.* |


![image](https://user-images.githubusercontent.com/96580515/175963232-46b784fb-6ab8-4e63-898a-581d862f9510.png)
|:--:| 
| *Figura 4. Estatística descritiva dos cinco itens mais frequentes de compra do ano de 2019.* |



A partir do ano de 2017, pneu foi um item de compra que esteve entre os cinco itens mais comprados e com maior valor médio homologado, enquanto o item papel, presente em todos os anos, apresentou menor  valor médio homologado.

Todas as estimativas do valor médio homologado apresentaram altos valores de desvio padrão, mostrando uma possível distribuição assimétrica dos dados.
Os valores de média e mediana apresentaram grande diferença, evidência que a média pode não ser representativa do conjunto de dados e que há a presença de valores extremos, influenciado as estimátivas da média.

Enquanto no ano de 2016 a quantidade média (4.121 ± 497,59)  dos cinco itens de compra mais frequente não teve grande variação, nos anos subsequentes (2017 (9.990 ± 1.789,52); 2018 (9.7565,6 ± 1.506,70); 2019 (10.713 ± 2.2027,70), a quantidade média dos itens aumentou.


#### Análises não prosseguidas

A fim de não se perder grande partes dos dados ao filtrar pela quantidade dos itens, foi tentado a realização da classificação dos texto a partir de modelo não supervisionado (Lbl2Vec). A construção de palavras-chave para tal classificação tomaria tempo.
Textos livres em forma de variáveis tomam grande quantidade de memória, impossibilitando a manipulação do mesmo quando carregava-se os arquivos dos quatro anos. Foi tentado a realização de *typecasting*, *lemmatization* e *TFIDF*.









