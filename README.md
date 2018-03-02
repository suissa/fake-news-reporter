# fake-news-reporter

Quando eu li essa notícia 
[Fake News: R$ 100 mil para quem ajudar a combater as falsidades](https://catracalivre.com.br/geral/cidadania/indicacao/fake-news/) na hora me veio uma solução BEM BESTA, vou explicar ela concisamente.

## Arquitetura de uma Fake News

Normalmente uma Fake News é gerada em cima de algum sujeito específico, podendo ser tanto uma pessoa como produto ou cryptomoeda.

Sabendo disso a primeira coisa que o sistema deverá fazer é analisar e definir qual o sujeito principal dessa notícia e quais outros sujeitos secundários existentes.

Se a notícia é falsa muito provavelmente não existe nenhuma outra notícia anterior, ligada ao sujeito, que corrobore essa atual.

Então nesse caso o sistema iria pesquisar todas notcias existentes sobre o sujeito principal e os secundários e pesar quais são suas relações.

A fonte de onde a notícia foi iniciada será avaliada pela sua idoneidade, quanto mais fontes com baixa avaliação replicarem essa notícia maior será seu grau de Fake News.
