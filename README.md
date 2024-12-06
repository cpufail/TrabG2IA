# Justificativa de IA escolhida

Para o meu segundo trabalho de Inteligencia Artificial eu selecionei o uso de uma rede neural, mais especificamente um classificador de bananas, onde ele classifica bananas baseadas em imagens cinzas as que estão totalmente lisas, ou seja, verdes ele irá rejeitas, já as maduras que são as que terão algumas marcas ele irá exportar, de inicio eu estava sem muitas ideias, porém eu estava em busca diante de milhares de datasets, foi então que eu olhei no google sala de aula que o professor tinha falado sobre datasets de bananas, logo fui atrás de datasets em relação a este assunto e eu me  encantei.


# Descrição e origem dataset

Bom, o dataset selecionado não é baseado em dados escritos e sim apenas por imagens, foi selecionado no universe.roboflow.com, o data set em exatos seria https://universe.roboflow.com/universitas-kuningan-zd6ub/model-pisang/browse?queryText=&pageSize=50&startingIndex=50&browseQuery=true possui imagens de bananas

# O Trabalho Possui
Pré-processamento das imagens,

criação do modelo,

treinamentos e ajustes,

classicação de exportação.

*As imagens foram redimensionadas para 80x80 pixels, convertidas para escala de cinza e normalizadas para valores entre 0 e 1.

*Foram atribuídos rótulos para cada imagem: 0 para a classe "rejeitado" e 1 para a classe "aprovado".

*O dataset foi dividido em conjuntos de treinamento: 830 amostras e validação: restante das amostras, correspondendo a cerca de 15% dos dados.


# Análise e conclusão

Seleciona 40 imagens para testes se a previsão foi maior que 0.5 as bananas irão para a exportação caso contrario sera rejeitado.

Concluindo, Por mais grande que o dataset pareça ele acaba limitando a capacidade do modelo, um dataset maior poderia melhorar o desempenho,
a maior dificuldade foi extrair o arquivo .zip que é o nosso dataset, eu não consegui extrair .csv, pois aparentemente não suporta imagens e sim apenas dados tabelados,





