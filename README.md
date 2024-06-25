# Classificação de imagens usando CNN com tensorflow

#### Para este projeto foi usada a base de dados ["Chest X-Ray Images (Pneumonia)"](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). Esta base contém imagens de raio-x de pessoas saudáveis e de pessoas com casos de pneumonia. Com isso, este projeto busca realizar a classificação dessas imagens entre casos normais e casos de pneumonia.

#### Requisitos:
* tensorflow
* numpy
* matplotlib
* jupyter notebook

#### Estrutura:
* CNN-ImageClassification.ipynb  - Notebook com o código utilizado para criação do modelo
* model_inferences/  - Inferência do modelo gerada no formato H5
* google_images/  - Algumas imagens de raio-x retiradas do google para testar no modelo

#### Como testar?
 Para testar o modelo com novas imagens, abra o notebook usando o jupyter, execute a primeira célula que contém os imports das bibliotecas necessárias e em seguida execute todas as células a partir da célula onde a inferência do modelo é carregada (no tópico "Salvando inferência do modelo").

#### Passos futuros:
* Buscar melhoria do modelo a partir do balanceamento da base de imagens (Atualmente: classe pneumonia > classe normal)
  * Uma possível solução se encontra [neste artigo](https://medium.com/analytics-vidhya/how-to-apply-data-augmentation-to-deal-with-unbalanced-datasets-in-20-lines-of-code-ada8521320c9) usando uma combinação de Data Augmentation com RandomOverSampling.
* Testar um número maior de valores para parâmetros.
* Testar adição de novas camadas ao modelo.
* Após melhorias, escrever texto no Medium explicando os passos de desenvolvimento do projeto.
  
