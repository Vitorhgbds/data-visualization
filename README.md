# data-visualization
fraud detection dataset


Use (this dataset) [https://www.kaggle.com/competitions/ieee-fraud-detection/data?select=train_transaction.csv]
# data processing:
1. Limpeza - precisa pegar todos os ids de usuários que já cometeram uma fraude, remover todos os usuários que nunca cometeram uma fraude.
2. Clustering - Mapear perfil dos usuários que cometeram uma fraude (separar em perfil 1, 2 ou 3...).
3. (x = atributo, y = count distinct id, stack = is_fraude) mapear os atributos para o eixo X e y sendo count distinct dos ids para descobrir os atributos que mais possuem impacto para realização de fraude.
4. Mapear addr para endereços que o power bi entenda.
5. manter informação de cartões.
6. remove unnecessary columns

INPUT DATA = train_transaction.csv
